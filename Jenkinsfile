pipeline {
  agent any
  stages {
    stage('print') {
      steps {
        echo 'testing'
      }
    }
    stage('build') {
      steps {
        sh './exec-jmeter.sh 3'
      }
    }
  }
}