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
                sh './mvnw clean install'
            }
        }

        stage('Test') {
            steps {
                sh './mvnw test'
            }
        }

    }
}
