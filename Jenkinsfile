pipeline {
  agent none
    stages {
      stage ('CleanWorkspace') {
        steps { always 
               { cleanWs()}
              }
      }
      stage ('Preparation'){
        steps{
          echo "CHECKING OUT CODE"
        }
      }
        stage ('Build'){
          steps{
            echo "Building Code"
            //echo ${mvnHome}
          }
        }
      stage ('Test'){
          steps{
            echo "Testing Code"
          }
        }
      stage ('Input'){
        steps {
         input "Do you want to continue?"
        }
        }
      stage ('Deploy'){
          steps{
            echo "Deploy Code"
          }
        }
      
    }
}
