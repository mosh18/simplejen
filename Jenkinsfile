pipeline {
    agent any

    stages {

        stage('Check Files') {
            steps {
                bat 'dir'
            }
        }

        stage('Deploy') {
            steps {
                bat 'xcopy /E /Y * C:\\deployed-app\\'
            }
        }

        stage('Success') {
            steps {
                echo 'Project deployed successfully'
            }
        }
    }
}