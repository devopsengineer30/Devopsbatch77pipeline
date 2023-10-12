pipeline {
  agent any
  stages {
    stage('Dev') {
      parallel {
        stage('Dev') {
          steps {
            echo 'development stage'
          }
        }

        stage('Test') {
          steps {
            echo 'Testing stage'
          }
        }

        stage('Plugin') {
          steps {
            echo 'Plugin stage'
          }
        }

      }
    }

    stage('QA') {
      steps {
        echo 'QA Stage'
      }
    }

    stage('UAT') {
      steps {
        echo 'UAT Stage'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy Stage'
      }
    }

    stage('Operate') {
      steps {
        echo 'Operate Stage'
      }
    }

  }
}