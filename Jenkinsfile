pipeline {
    agent any
    stages {
        stage('Build & Push') {
            steps {
                sh 'docker build -t riishaall/app5:latest .'
                sh 'docker push riishaall/app5:latest'
            }
        }
    }
}
