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
      sh '/opt/sonar-scanner/bin/sonar-scanner -Dsonar.login=2f881e6b766ab3328f5f905b846f12deead6361a'
      }
    }
  }
}
