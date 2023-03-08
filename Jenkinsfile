pipeline {
  agent any
  stages {
    stage('install') {
      steps {
        sh 'sudo apt install awscli'
      }
    }

    stage('build') {
      steps {
        sh 'echo "build stage"'
      }
    }

    stage('deploy') {
      steps {
        sh 'echo "deploy step"'
      }
    }

  }
}