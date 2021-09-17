pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build avec succes '
      }
    }

    stage('test ') {
      parallel {
        stage('test ') {
          steps {
            echo 'test avec succes '
          }
        }

        stage('test 1 ') {
          steps {
            echo 'test 1 succes '
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy avec succes '
      }
    }

  }
}