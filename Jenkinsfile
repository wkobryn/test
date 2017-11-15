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
      }
    }
  }
}