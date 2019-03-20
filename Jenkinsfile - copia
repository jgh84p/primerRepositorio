pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'docker buld -t app.'
      }
    }
    stage('Test'){
			steps{
				echo 'TEST'
			}
		}		
    stage('Deploy') {
      steps {
        echo 'DEPLOY'
      }
    }
  }
}
