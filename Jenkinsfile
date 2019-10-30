pipeline {
  agent any
  stages{
    stage('Build'){
      steps{
        withMaven(maven:'localMaven'){
          sh 'mvn clean package'
        }
      }
    }
  }
}
