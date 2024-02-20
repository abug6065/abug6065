pipeline {
    agent any
    stages {
        stage('Git Clone') {
            steps {
                script {
                    // Clone the repository using specific credentials
                    git branch: 'main', credentialsId: 'github', url: 'https://github.com/abug6065/abug6065.git'
                }
            }
        }
    }
}

