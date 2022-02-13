pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'mvn compile'
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
