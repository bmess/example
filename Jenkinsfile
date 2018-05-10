pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'python -m pytest -v --junit-file=junit.xml'
      }
    }
  }
}
