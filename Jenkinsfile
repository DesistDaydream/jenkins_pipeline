pipeline {
  agent { docker 'golang' }
  stages {
    stage('run') {
      steps {
        sh 'go run main.go'
      }
    }
  }
}
