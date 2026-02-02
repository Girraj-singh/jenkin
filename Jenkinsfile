pipeline {
    agent any

    stages {

        stage('Clone Repo') {
            steps {
                echo 'Cloning GitHub repository...'
            }
        }

        stage('Build') {
            steps {
                echo 'Build step running...'
                ls
            }
        }

        stage('Test') {
            steps {
                echo 'No tests configured yet'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment step will be added later'
            }
        }
    }

    post {
        success {
            echo 'Pipeline executed successfully ✅'
        }
        failure {
            echo 'Pipeline failed ❌'
        }
    }
}
