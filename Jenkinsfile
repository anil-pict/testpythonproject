pipeline {
  agent {
    node {
      label 'windows_slave_agent'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'This is Jenkinsfile from development branch'
        bat 'SET Path=%PATH%;C:\\Tools\\Python392;'
        bat 'python my.py'
      }
    }

  }
  environment {
    myenv1 = 'val1'
    myenv2 = 'val2'
  }
}