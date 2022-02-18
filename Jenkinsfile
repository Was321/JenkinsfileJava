pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'mvn compile but jksak'
            }
        }
        stage('Test') {
            steps {
                echo 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'mvn package'
            }
        }
    }
}
