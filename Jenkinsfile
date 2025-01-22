pipeline {
    agent any
    environment {
        GIT_SSH_KEY = credentials('id_ed25519.pub')
    }
    stages {
        stage('Checkout') {
            steps {
                git url: 'git@github.com:subramaniravi/node-2.git', credentialsId: 'id_ed25519.pub'
            }
        }
    }
}


