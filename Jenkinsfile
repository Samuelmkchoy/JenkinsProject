pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    echo 'Hello from Jenkins!'
                    sh 'java -version'
                }
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
