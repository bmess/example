pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'python -m pytest -v --junitxml=junit.xml'
        junit 'junit.xml'
      }
    }
  }
}
