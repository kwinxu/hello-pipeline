pipeline {
  agent any

  stages {
    stage('run worktile stop docker') {
      steps {
        sh 'docker ps -a'
      }
    }

    stage('Using Worktile Pipeline') {
      steps {
        sh 'wtctl.sh'
      }
    }
  }
}