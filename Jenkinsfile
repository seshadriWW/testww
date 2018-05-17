pipeline {
  agent any
  stages {
    stage('Pipeline Start') {
      steps {
        echo 'Pipeline Started'
      }
    }
    stage('echo maven') {
      steps {
        sh 'whoami'
      }
    }
    stage('sonar') {
      steps {
        sh 'mvn sonar:sonar'
      }
    }
  }
}