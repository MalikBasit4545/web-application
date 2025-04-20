pipeline {
    agent any

    stages {
        stage('Install Dependencies') {
            steps {
                sh 'echo "Installing dependencies..."'
                // Replace with actual dependency installation commands
            }
        }
        stage('Run Tests') {
            steps {
                sh 'echo "Running test script..."'
                // Replace with your test script command
                // Example: sh 'npm test'
            }
        }
        stage('Archive Artifacts') {
            steps {
                archiveArtifacts artifacts: '**/*.html', fingerprint: true
            }
        }
    }
}
