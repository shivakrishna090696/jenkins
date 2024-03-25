pipeline {

    agent any
    stages {
        stage('checkout source') {
            steps {
                git branch: 'main', url: 'https://github.com/shivakrishna090696/jenkins.git'
            }
        }
        stage('docker build') {
            steps {
                script {
                    sh 'sudo docker build -t shivakrishna .'
                }
            }
        }
    }    
}
