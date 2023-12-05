pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo "stage1"'
          }
        }

        stage('Stage2') {
          steps {
            sh 'echo "stage2"'
          }
        }

      }
    }

  }
}