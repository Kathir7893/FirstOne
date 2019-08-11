pipeline {
  agent any
  stages {
    stage('myStage'){
      steps {
        sh 'ls -la'
	sh 'df -TPh'
	sh 'whoami; hostname'
      }
    }
    stage('Build') {
      steps { 
        sh 'ls' 
      }
    }
  }
}
