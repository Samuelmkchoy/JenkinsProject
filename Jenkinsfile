pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from the remote repository
                git 'https://github.com/Samuelmkchoy/JenkinsProject'
            }
        }

        stage('Build') {
            steps {
                // Build your project, replace 'your-build-command' with the actual build command
                sh 'your-build-command'
            }
        }
    }

    post {
        success {
            echo 'Build successful! Add additional steps for deployment or further actions.'
        }
        failure {
            echo 'Build failed. Take necessary actions for failure handling.'
        }
    }
}
