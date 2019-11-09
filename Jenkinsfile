pipeline {
  agent any
  stages {
    stage('myStage'){
      steps {
        sh 'ls -la' 
      }
    }
    stage('Test') {
      steps { 
        sh 'yarn & yarn test' 
      }
    }
  }
}