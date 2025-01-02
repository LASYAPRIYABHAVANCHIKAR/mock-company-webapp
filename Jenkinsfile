pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh './gradlew assemble' // Build step
            }
        }
        stage('Test') {
            steps {
                sh './gradlew test' // Test step
            }
        }
    }
}

