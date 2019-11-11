pipeline {
  agent any
  stages {
    stage('Verified'){
      steps {
        sh 'ls -la' 
      }
    }
    stage('Test') {
      steps { 
        sh 'yarn install' 
        sh 'yarn start' 
      }
    }
  }
}