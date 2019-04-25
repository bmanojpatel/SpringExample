pipeline {
  agent {
    docker {
      image 'maven 3.3'
      args 'mvn clean install'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}