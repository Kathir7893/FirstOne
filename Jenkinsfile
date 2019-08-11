pipeline {
  agent any
  stages {
    stage('myStage'){
      steps {
        sh 'ls -la'
	sh 'df -TPh'
	sh 'whoami; hostname'
	sh 'hostname -f; hostnae -i;w;free -m'
      }
    }
    stage('Build') {
      steps { 
        sh 'ls' 
      }
    }
  }
}
