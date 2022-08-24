pipeline {
    agent {
        docker {
               image 'node:14-alpine'
               alwaysPull true
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'pwd'
                sh 'node - -version' 
            }
        }
    }
}
