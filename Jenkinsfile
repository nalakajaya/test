pipeline { 
  agent any
stages{
   stage('Build'){
        steps{
              echo "Build"
              echo "Build1"
               echo "Build2"
              
         }
     }
   stage('Init'){
        parallel{
             stage('P1'){steps{ echo "launch p1 in background"}}
             stage('setup'){steps{echo "setup"}}
           }
     }
   stage('Group'){
        parallel{
             stage('P1'){steps{  parallel("b1": { echo "p1"})}}
             stage('P2'){steps{ parallel("b2": {echo "p2"})}}
             stage('P3'){steps{ parallel("b3":{echo "p3"})}}
           }
     }
      stage('ParallelSteps'){
     steps {       
        parallel(
            "a1": {  echo "ps1"},
          "a2":  { echo "ps2"},
         "a3":  {   echo "ps3"}
           )
     }
     }

   stage('Cleanup'){
        steps{
              echo "cleanup"
         }
     }
   stage('Check P1 status'){
        steps{
              echo "Check"
         }
     }
  stage('S2'){
        steps{
              echo "S2"
         }
     }
}


}
