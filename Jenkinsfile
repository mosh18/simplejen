pipeline {
    agent any

    stages {

        stage('Check Files') {
            steps {
                bat 'dir'
            }
        }

        stage('Run Server') {
            steps {
                bat 'node server.js'
            }
        }
    }
}