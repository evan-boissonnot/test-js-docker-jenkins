pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        git(url: 'https://github.com/evan-boissonnot/test-js-docker-jenkins', changelog: true, branch: 'master')
      }
    }
  }
}