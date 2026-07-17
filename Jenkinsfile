pipeline {

    agent any

    stages {

        stage('Check Code') {
            steps {
                sh 'git log -5 --oneline'
                sh 'ls -la'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing application'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application'
            }
        }
    }
}
