pipeline {
    agent any

    stages {
        stage('Checking version') {
            steps {
                sh 'javac -version'
            }
        }
        stage('Compiling') {
            steps {
                sh 'javac Hello.java'
            }
        }
        stage('Running') {
            steps {
                sh 'java Hello'
            }
        }
    }
}
