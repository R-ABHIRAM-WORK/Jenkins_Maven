pipeline {
    agent any
    tools {
        maven 'Maven' // Changed from 'MAVEN_HOME' to 'Maven'
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
} 