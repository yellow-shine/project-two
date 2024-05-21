pipeline {
      agent {
            label 'arm'
        }
    stages {
        stage('Build') {
            steps {
                sh """
                ls -lrta
                echo "reading..."
                cat README.md
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
