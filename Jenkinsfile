pipeline {
  agent any
  stages {
    stage('Version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('STAGE2') {
      steps {
        sh 'python3 python.py $X_VALUE $Y_VALUE'
      }
    }
  }
}
