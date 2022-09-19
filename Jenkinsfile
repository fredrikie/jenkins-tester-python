pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('message steve') {
      steps {
        sh 'python3 /scripts/sendmail.py'
      }
    }
  }
}
