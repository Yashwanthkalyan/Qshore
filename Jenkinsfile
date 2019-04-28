pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'bulding '
      }
    }
    stage('Unit test') {
      steps {
        timeout(time: 4, unit: 'HOURS')
        echo 'Unit testing'
      }
    }
    stage('QA') {
      steps {
        echo 'QA'
      }
    }
    stage('Delivery') {
      steps {
        echo 'final'
      }
    }
  }
}