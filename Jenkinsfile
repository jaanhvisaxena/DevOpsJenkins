/* Requires the Docker Pipeline plugin */
pipeline {
    agent {
        docker {
            image 'maven:3.9.9-eclipse-temurin-21-alpine'
        }
    }
    stages {
        stage('Build') {
            steps {
                // Replace with your real Maven build command if needed
                sh 'mvn --version'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('Hello') {
            steps {
                echo 'hello from Jenkins pipeline 500101756'
            }
        }
    }
}
