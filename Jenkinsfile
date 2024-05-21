pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh """
                sleep 360
                """
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
