pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
    post {

        always {
            echo 'This runs ALWAYS (success or failure)'
        }

        success {
            echo 'This runs only if pipeline SUCCESS'
        }

        failure {
            echo 'This runs only if pipeline FAILS'
        }
    }
}
