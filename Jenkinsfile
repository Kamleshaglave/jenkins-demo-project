pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/Kamleshaglave/jenkins-demo-project.git'
            }
        }

        stage('Docker Build') {
            steps {
                sh 'docker build -t kamlesh-devops-app .'
            }
        }

        stage('Docker Deploy') {
            steps {
                sh '''
                docker stop kamlesh-container || true
                docker rm kamlesh-container || true
                docker run -d -p 8081:80 --name kamlesh-container kamlesh-devops-app
                '''
            }
        }
    }
}
