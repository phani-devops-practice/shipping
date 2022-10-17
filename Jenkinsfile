pipeline {
  agent any
  options {
    ansiColor('xterm')
  }
  stages {
    stage('Compile packages') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}