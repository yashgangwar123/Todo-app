pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Application Building....'
                nodejs('NodeJS-todo') {
                    sh 'npm install'
                    sh 'npm build'
                }
            }
        }
        stage('Test') {
            steps {
                echo 'Application Testing....'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Application Deploying....'
            }
        }
    }
}
