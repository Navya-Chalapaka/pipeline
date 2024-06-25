pipeline {
  agent any
  stages {
    stage('Dev') {
      parallel {
        stage('Dev') {
          steps {
            echo 'development'
          }
        }

        stage('plugin') {
          steps {
            echo 'plugin'
          }
        }

        stage('test') {
          steps {
            echo 'test'
          }
        }

      }
    }

    stage('UAT') {
      steps {
        echo 'uat stage'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

    stage('operate') {
      steps {
        echo 'rate'
      }
    }

  }
}
