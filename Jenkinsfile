pipeline {
    agent any
    stages {
        stage('Compile Source Code') {
            steps {
                sh 'mvn compile'  // Replace with your build command
            }
        }
        stage('Test Source Code') {
            steps {
                sh 'mvn test'  // Replace with your test command
            }
        }
        stage('Package Code') {
            steps {
                sh 'mvn package'  // Replace with your packaging command
            }
        }
    }
}
