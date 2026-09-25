pipeline {
    agent any

    stages {

        stage('Checkout SCM') {
            steps {
                checkout scm
            }
        }

        stage('compile') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }

        stage('run') {
            steps {
                bat 'java HelloWorld'
            }
        }
    }
}
