pipeline {
  agent any
      triggers {
        githubPush()
    }
  stages {
    stage('Build') {
      steps {
        sh 'ls -la'
      }
    }
  }
}
