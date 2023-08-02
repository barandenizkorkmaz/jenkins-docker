#!groovy
pipeline{
  agent none
  stages{
    stage('Test - Docker'){
      agent{
        docker{
          image 'node:latest'
        }
      }
      steps{
        sh 'node --version'
      }
    }
  }
}