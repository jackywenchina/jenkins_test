pipeline {
  agent any

  stages {
    stage('Example stage 1') {
      environment {
        ADMIN = credentials('dd53adef-f3d2-4f5b-a815-272675c3cba7')
      }

      steps {
        sh 'printenv'
      }
    }
  }
}