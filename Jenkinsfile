pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build..'
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Testing..'
          }
        }

        stage('Testing FireBox') {
          steps {
            echo 'Testing FireBox Testing Chrome browder'
          }
        }

        stage('Testing Chrome') {
          steps {
            echo 'Testing Chrome browder'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

  }
}
