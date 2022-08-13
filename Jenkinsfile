pipeline {
    agent {
        docker {
            image 'node:lts-alpine3.16' 
            args '-p 8018:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
