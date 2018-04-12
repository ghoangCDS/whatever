pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('stage6') {
      agent {
        docker {
          image 'maven:alpine'
        }
        
      }
      steps {
        echo 'hello'
        sh 'mvn -v'
        echo 'Hello'
        timestamps()
      }
    }
  }
}