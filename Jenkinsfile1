pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'This is Jenkinsfile from development branch'
        sh 'python3 my.py'
      }
    }

  }
  environment {
    myenv1 = 'val1'
    myenv2 = 'val2'
  }
}

