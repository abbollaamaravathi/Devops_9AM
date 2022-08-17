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

      }
    }

  }
}