pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat 'docker-compose up'
      }
    }

    stage('test') {
      steps {
        echo 'This is a test!!!!!!!'
      }
    }

    stage('deploy') {
      steps {
        echo 'Deployment is running here'
      }
    }

  }
}