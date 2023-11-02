pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                // sh 'pip install -r requirements.txt' // Install project dependencies (if any)
                sh 'pytest'  // Run pytest
            }
        }
    }
}

