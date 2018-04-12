library 'SharedLibs'

pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('stage6') {
      steps {
        echo 'hello'
        sh 'mvn -v'
        echo 'Hello'
      }
    }
    
    stage('Shared Lib') {
      steps {
        helloWorld("Jenkins")
      }
    }
    
    
  }
}
