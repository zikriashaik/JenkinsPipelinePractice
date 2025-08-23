pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'Initialized'
      }
    }

    stage('Input') {
      steps {
        echo 'UserInput'
      }
    }

    stage('App Vers Check') {
      parallel {
        stage('App Vers Check') {
          steps {
            echo 'test'
          }
        }

        stage('CB Validate') {
          steps {
            echo 'test1'
          }
        }

      }
    }

    stage('kafka check') {
      steps {
        echo 'final'
      }
    }

  }
}