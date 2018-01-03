pipeline {
  agent any
  stages {
    stage('Group Deployments') {
      parallel {
        stage('Stage1') {
          steps {
            echo 'Msg1'
          }
        }
        stage('') {
          steps {
            echo 'Step 2'
          }
        }
        stage('Stage3') {
          steps {
            echo 'Step 3'
          }
        }
      }
    }
  }
}