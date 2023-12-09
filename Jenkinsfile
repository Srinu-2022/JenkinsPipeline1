pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Add Build Operation'
          }
        }

        stage('Test') {
          steps {
            echo 'Test Operation'
          }
        }

        stage('Deploy') {
          steps {
            echo 'Deploy the app'
          }
        }

      }
    }

    stage('Implement') {
      steps {
        echo 'Implement the steps'
      }
    }

  }
}