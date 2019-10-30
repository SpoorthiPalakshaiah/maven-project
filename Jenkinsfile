pipeline {
  agent any
  stages{
    stage('Build'){
      withMaven(maven:'localMaven'){
        sh 'mvn clean package'
      }
    }
  }
}
