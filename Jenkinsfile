pipeline {
  agent any
  stages{
  stage ('build'){
    steps{
    bat 'mvn clean'
      }
    }
    stage ('codeAnalysis'){
      withSonarQubeEnv('Sonar'){
        bat 'mvn sonar:sonar'
      }
    }
 }
  post { 
   always { 
         echo 'I will always say Hello again!'
    }
  }
}
