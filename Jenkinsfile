

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {

            }
        }
        stage('Test') {
            agent {
                dockerfile true
            }

            steps {
                sh 'python hap.py'
            }
        }
    }
}