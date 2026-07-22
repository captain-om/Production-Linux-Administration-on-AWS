pipeline {

    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'main',
                url: 'https://github.com/captain-om/Production-Linux-Administration-on-AWS.git'
            }
        }

        stage('Environment') {
            steps {
                sh '''
                echo "========== SYSTEM =========="
                hostname
                whoami
                pwd
                uname -a
                '''
            }
        }

        stage('Git Validation') {
            steps {
                sh '''
                git status
                git log --oneline -3
                '''
            }
        }

        stage('Repository Validation') {
            steps {
                sh '''
                ls -la
                '''
            }
        }

        stage('PHP Validation') {
            steps {
                sh '''
                php -v
                composer --version
                '''
            }
        }

        stage('Build Complete') {
            steps {
                echo 'Pipeline completed successfully.'
            }
        }
    }
}
