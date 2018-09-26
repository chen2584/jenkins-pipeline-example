pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls'
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                sh 'date'
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                sh 'pwd'
                echo 'Deploying....'
            }
        }
    }
}