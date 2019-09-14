pipeline {
  agent any
  stages {
    stage('Stage 1') {
      parallel {
        stage('Stage 1') {
          steps {
            echo 'Hello world 002!'
          }
        }
        stage('Stage2') {
          steps {
            echo 'This is step 1 of stage 2'
          }
        }
      }
    }
  }
}