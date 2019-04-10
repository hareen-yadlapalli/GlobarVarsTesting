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
        println "${DBUser}"
      }
    }
  }
}
