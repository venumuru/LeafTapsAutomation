pipeline {
  agent any
  stages {
    stage('Pull from GIT') {
      steps {
        git(url: 'https://github.com/venumuru/LeafTapsAutomation', branch: 'master', poll: true)
        echo 'Code pulled from git'
      }
    }

    stage('Smoke test') {
      steps {
        echo 'Start smoke test'
      }
    }

    stage('Build certify') {
      steps {
        echo 'Build certification'
      }
    }

  }
}