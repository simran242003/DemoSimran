pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Checkout code from GitHub
                git 'https://github.com/simran242003/DemoSimran.git'
            }
        }
        stage('Build') {
            steps {
                // Example build step (e.g., compile Java code)
                echo 'Building the project...'
                sh 'mvn clean install'  // Replace with your build commands if necessary
            }
        }
        stage('Test') {
            steps {
                // Run tests (e.g., unit tests)
                echo 'Running tests...'
                sh 'mvn test'  // Replace with your test commands if necessary
            }
        }
        stage('Deploy') {
            steps {
                // Example deploy step
                echo 'Deploying the project...'
                // Add your deploy commands here
            }
        }
    }
}
