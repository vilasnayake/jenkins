pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                echo 'Compiling code'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing the application...'
                echo 'Running unit tests - All tests passed!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to production...'
                echo 'Deployment successful! App is live.'
            }
        }
    }
}
