pipeline {
  agent any
  environment {
    AAA_TOP_LEVEL_VAR = 'topLevel'
  }
  stages {
    stage('stage 1') {
      steps {
        sh 'echo $AAA_TOP_LEVEL_VAR'
        sh 'env | sort'
      }
    }
  }
}
