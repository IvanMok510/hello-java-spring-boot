pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                script {
                    echo "Starting to clone code..."
                    // This is done automatically by SCM setting
                    echo "Current workspace: ${env.WORKSPACE}"
                    sh 'ls -la'
                }
            }
        }
    }
}
