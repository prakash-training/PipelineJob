pipeline{
agent any
     stages{
            stage('git clone'){
                steps{
                      sh 'echo downloading code' 
                     }
              } 
              
              stage('compiling'){
                steps{
                      sh 'echo compiling code' 
                     }
              }
              
              stage('building'){
                steps{
                      sh 'echo building code' 
                     }
              }
          
          stage('get approval'){
                steps{
                      input 'please approve the deployment' 
                     }
          }
          
           stage('deployment'){
                steps{
                      sh 'echo code is deploying' 
                     }
              }
              
           }

}
