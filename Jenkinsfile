pipeline {
  agent none
  stages {
    stage('Build') {
      agent any
      steps {
        mvn -f pom.xml clean compile
        echo 'Hello World'
      }
    }
  }
}
