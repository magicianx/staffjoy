pipeline {
  agent any
  stages {
    stage('Source') {
      steps {
        git 'https://github.com/magicianx/staffjoy.git'
      }
    }

  }
  environment {
    COMPLETED_MSG = 'Build done!'
  }
}