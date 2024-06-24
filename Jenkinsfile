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
            echo '1111Testing..'
          }
        }

        stage('Testing FireBox') {
          steps {
            echo '1111Testing FireBox Testing Chrome browder'
          }
        }

        stage('Testing Chrome') {
          steps {
            echo '111Testing Chrome browder'
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
