pipeline {
  agent any
  triggers{
    cron('H/15 * * * *')
  }
  stages {
    stage('Echoing a file') {
      steps {
        sh 'echo "This a file from version control, 11th commit"'
      }
    }

  }
}
