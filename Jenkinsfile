pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checkout stage'
            }
        }

        stage('Build') {
            steps {
                bat 'mvnw.cmd clean install'
            }
        }

        stage('Test') {
            steps {
                bat 'mvnw.cmd test'
            }
        }
    }
}
