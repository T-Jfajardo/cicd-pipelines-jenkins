pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'test'
      }
    }

    stage('deploy') {
      steps {
        input(message: 'deploy to dev', id: '1', ok: 'OK', submitter: 'Author', submitterParameter: 'Author')
      }
    }

  }
  environment {
    dev = 'dev'
  }
}