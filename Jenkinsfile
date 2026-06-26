pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Show Files') {
            steps {
                sh 'pwd'
                sh 'ls -la'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Hello from Jenkins!"'
                sh 'date'
                sh 'uname -a'
            }
        }

        stage('Success') {
            steps {
                echo '🎉 Build completed successfully!'
            }
        }
    }
}
