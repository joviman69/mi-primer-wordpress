pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        node(label: 'default') {
          sh 'cat /etc/os-release'
        }

      }
    }
  }
}