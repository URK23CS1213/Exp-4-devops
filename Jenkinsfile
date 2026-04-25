pipeline {
    agent any
    stages {
        stage('Build & Push') {
            steps {
                sh 'docker build -t gautham55/app5:latest .'
                sh 'docker push gautham55/app5:latest'
            }
        }
    }
}
