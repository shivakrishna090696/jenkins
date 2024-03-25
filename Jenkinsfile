pipeline {

    agent any
    stages {
        stage('checkout source') {
            steps {
                git 'https://github.com/shivakrishna090696/jenkins.git'
            }
        }
        stage('Docker Build) {   
            steps {
                script{
                        sh "docker build -t shivakrishna ."
                }
            }
        }
    }    
}
