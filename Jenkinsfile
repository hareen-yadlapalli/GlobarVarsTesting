pipeline {
  agent any
  stages {
    stage('Initialise Variables') {
      steps {
        script {
          DBUser="demouser"
        }

      }
    }
    stage('Print Variables') {
      steps {
        echo 'Database user is ${DBUser}'
      }
    }
  }
}