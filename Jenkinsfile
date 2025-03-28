pipeline {
    agent { docker { image 'maven:3.9.9-eclipse-temurin-21-alpine' } }

    stages {
        stage('Build') {
            steps {
                sh 'mvn --version'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }

        stage('Hello') {
            steps {
                echo 'hello from Jenkins pipeline 500101756'
            }
        }
    }
}
