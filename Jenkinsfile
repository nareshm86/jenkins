pipeline {
    agent {
        node {
            label 'ROBOSHOP'
        }
    }

    stages {
        stage('Build') {
            steps {
                sh '''
                    echo 'Building..'
                '''
            }
        }

        stage('Test') {
            steps {
                sh '''
                    echo 'Testing....done'
                '''
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                    echo 'Deploying...'
                '''
            }
        }
    }
}