pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo "Cloning repository..."
            }
        }

        stage('Build') {
            steps {
                echo "Build Stage Running..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying to Apache..."
                sh 'cp -r * /var/www/html/'
            }
        }
    }
}
