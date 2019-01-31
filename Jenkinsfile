pipeline {
    agent {
        docker {
            image '10.12.0-alpine'
            arg '-p 3000:3000'
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