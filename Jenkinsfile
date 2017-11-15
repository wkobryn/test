pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "BUILD"'
      }
    }
    stage('deploy') {
      steps {
        pwd(tmp: true)
        input(message: 'Proceed ?', id: '1', ok: 'aaa', submitter: 'ss', submitterParameter: 'sdsd')
      }
    }
  }
}