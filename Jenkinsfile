pipeline {
  agent any
  stages {
    stage('start') {
      steps {
        bat 'hello'
      }
    }
    stage('sleep') {
      steps {
        sleep 3
      }
    }
    stage('email') {
      steps {
        mail(subject: 'Some email', body: 'Hello there', from: 'anill.sangroula@uscellular.com')
      }
    }
  }
}