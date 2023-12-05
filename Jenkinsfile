pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          agent {
            node {
              label 'nodelinux'
            }

          }
          steps {
            sh 'echo "stage1"'
          }
        }

        stage('Stage2') {
          agent {
            node {
              label 'nodelinux'
            }

          }
          steps {
            sh 'echo "stage2"'
          }
        }

      }
    }

  }
}