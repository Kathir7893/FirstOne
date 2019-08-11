pipeline {
  agent any
  stages {
    stage('myStage'){
      steps {
        sh 'ls -la'
	sh 'df -TPh'
      }
    }
    stage('Build') {
      steps { 
        sh 'ls' 
      }
    }
  }
}
