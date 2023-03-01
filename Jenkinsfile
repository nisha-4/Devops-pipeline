pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
         stage('Test') {
            steps {
                echo 'Hello World'
            }
        }
         stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Deploy1') {
            steps {
                echo 'Hello World'
            }
        }
         stage('Deploy2') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post
    {
        always {
            emailext body: 'hi', subject: 'jenkins', to: 'nishaangelic492000@gmail.com'
        }
    }
}
