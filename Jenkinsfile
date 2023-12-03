pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Hello from Jenkins!"
                java -version
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
