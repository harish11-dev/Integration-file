pipeline {
  agent any 
  stages {
    stage('build'){
      steps{
      sh 'mvn clean install'
      }
    }
    stage('sonarcodeanalysis'){
      steps{
      sh 'sonarscanner'
      }
    }
  }
}
