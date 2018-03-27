pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh './gradlew test'
            }
        }
        stage('Test') {
            steps {
               sh './gradlew test'
            }
        }
    }
}