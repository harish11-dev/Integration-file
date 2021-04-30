pipeline {
  agent any 
  stages {
    stage "build" {
      steps {
      sh "mvn clean install"
    }
  }
    stage "sonarcodeanalysis" {
      sh "sonarscanner(arg1,arg2)" 
    }
  }
}


