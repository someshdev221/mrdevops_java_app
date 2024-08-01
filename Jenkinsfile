pipeline {
    agent any

    stages {
        stage('Clean Workspace') {
            steps {
                cleanWs() // Clean workspace before starting
            }
        }

        stage('Checkout from Git') {
            steps {
                script {
                    // Checkout code from the specified Git repository and branch
                    git branch: 'main', url: 'https://github.com/someshdev221/mrdevops_java_app.git'
                }
            }
        }
    }
}
