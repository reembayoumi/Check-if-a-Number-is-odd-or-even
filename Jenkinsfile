pipeline {
    agent none
    stages {
        stage('Build') {
             agent {
                docker {
                    image 'python:3.8.2-alpine' 
                }
            }
            steps {
                sh 'python numberevenorodd.py'
            
            }
        }
    }
}
