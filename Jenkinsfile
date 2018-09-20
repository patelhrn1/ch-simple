pipeline {
  agent none
  stages {
    stage('Build') {
      agent any
      steps {
        sh 'mvn clean compile'
        echo 'Hello World'
      }
    }
  }
}
