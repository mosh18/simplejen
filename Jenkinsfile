pipeline {
    agent any

    stages {

        stage('Check Files') {
            steps {
                bat 'dir'
            }
        }

        stage('Start Server') {
            steps {
                bat 'start /B node server.js'
            }
        }

        stage('Success') {
            steps {
                echo 'HTML server started successfully'
            }
        }
    }
}