pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'php -v'
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy'
            }
        }
    }
}
