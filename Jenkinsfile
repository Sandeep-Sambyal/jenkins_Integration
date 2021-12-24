pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
    }

    post {
        failure {
            // send to email
            echo 'FAILED.....'

        }
    }
}
