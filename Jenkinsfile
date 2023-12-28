pipeline {
  agent {
    node {
      label 'agent1'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn clean install'
      }
    }

  }
}