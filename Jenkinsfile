pipeline {
  agent any
  stages {
    stage('jenkini') {
      steps {
        git(url: 'https://github.com/dku32180889/jenkinsfile.git', branch: '*/master')
      }
    }

    stage('Build') {
      steps {
        tool 'gradle'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo "hello world"'
      }
    }

  }
}