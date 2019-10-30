pipeline {
  agent any
  tools {
        maven 'Maven 3.2.6'
    }
  stages{
    stage('Build'){
      steps{
        sh 'mvn clean package'
      }
    }
  }
}
