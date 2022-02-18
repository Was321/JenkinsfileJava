pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'mvn compile but wasim is good'
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
