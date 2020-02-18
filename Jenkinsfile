pipeline {
  agent any
  stages {
    stage('Init') {
      parallel {
        stage('Init') {
          steps {
            sh 'echo "Initialisation"'
          }
        }

        stage('Init Bis') {
          steps {
            sh 'echo "Initialisation BIS"'
          }
        }

      }
    }

    stage('Step 1') {
      steps {
        sh 'hostname'
      }
    }

  }
}