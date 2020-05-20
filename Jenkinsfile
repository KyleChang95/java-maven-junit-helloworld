pipeline {
   agent any

   tools {
      maven "maven 3.5"
   }

   stages {
    stage('checkout project') {
      steps {
        checkout scm
      }
    }
  }
}
