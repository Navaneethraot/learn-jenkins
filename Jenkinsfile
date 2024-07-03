pipeline {
    agent {
        label 'AGENT -1'
    }
    options {
        timeout (time :1, unit; 'MINUTE')
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo this is build'
            }
        }
        stage('Test') {
            steps {
                sh 'echo this is test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo this is deploy'
            }
        }
    }
}