pipeline {
  agent any
  stages{
    stage('Build'){
        def mvn_version = 'localMaven'
        withEnv( ["PATH+MAVEN=${tool mvn_version}/bin"] ) {
            sh 'mvn clean package'
      }
    }
  }
}
