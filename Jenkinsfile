pipeline {
  agent any
  stages {
    stage('Inicio') {
      steps {
        echo 'Hola mundo'
      }
    }
    post {
      always{
        echo 'mensaje desde el always de post'
      }
      
      success {
        echo 'mensaje desde el succes de post'
      }
    }
    stage('Test2') {
      steps {
        echo 'hola paso 2'
      }
    }
  }
}
