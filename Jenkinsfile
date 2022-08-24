pipeline {
    agent any
    
    tools {nodejs "nodejs"}

    stages {
        stage('Build') {
            steps {
                sh 'ls'
            }
        }
        stage('test') {
            steps {
                sh 'npm i'
            }
        }
    }
}
