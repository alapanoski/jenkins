pipeline {
    agent { 
      docker { 
        image 'maven:3.8.6-eclipse-temurin-11' 
      } 
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn'
            }
        }
    }
}