pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'sudo yum install python3-pip -y'
        sh 'pip install -r requirements.txt'
        sh 'python3 app.py'
      }
    }
  }
}
