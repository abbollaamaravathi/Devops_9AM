pipeline {
  agent any
  stages {
    stage('step1') {
      parallel {
        stage('step1') {
          steps {
            sh 'echo "hello"'
          }
        }

        stage('stape1.1') {
          steps {
            sh 'echo "goodmorning"'
          }
        }

        stage('step1.3') {
          steps {
            sh 'echo "welcome"'
          }
        }

      }
    }

    stage('step2') {
      parallel {
        stage('step2') {
          steps {
            sh 'echo "welcome"'
          }
        }

        stage('step1.2') {
          steps {
            sh 'echo "welcome to devops"'
          }
        }

        stage('step1.4') {
          steps {
            sh 'echo "hello step 1.4"'
          }
        }

      }
    }

  }
}