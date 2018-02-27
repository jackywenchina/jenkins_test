pipeline {
  agent any

  stages {
    stage('Example stage 1') {
      environment {
        ADMIN = credentials('admin')
      }

      steps {
        sh 'printenv'
      }
    }
  }
}