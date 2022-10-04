pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
        withMaven(jdk: 'Java SDK 9.0.4', maven: 'Maven') {
        sh 'mvn clean install'
        }

      }
    }

  }
}
