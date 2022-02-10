pipeline {
  agent any
  stages {
    stage('git pull code') {
      steps {
        echo 'git pull code'
      }
    }
    stage('run unit test') {
      steps {
        echo 'run unit test'
      }
    }
    stage('build docker') {
      steps{
        echo 'build docker'
      }
    }
    stage('deploy') {
      steps{
        echo 'deploy'
      }
    }
  }
}