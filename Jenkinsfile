pipeline {
  agent any
  stages{
  stage ('build'){
    steps{
    bat 'mvn clean'
  }
  }
 }
  post { 
        always { 
            echo 'I will always say Hello again!'
        }
  }
}
