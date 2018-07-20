pipeline {
  agent any
  stages {
    stage('preparation') {
      steps {
        echo 'hello the is prep stage'
      }
    }
    stage('build') {
      steps {
        echo 'this is build stage'
      }
    }
    stage('sonarqube') {
      steps {
        echo 'this is for code quality check'
      }
    }
    stage('performance') {
      steps {
        echo 'this is for performance'
      }
    }
  }
}