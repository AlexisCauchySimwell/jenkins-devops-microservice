
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Build"
            }
        }

        stage('Test') {
            steps {
                echo "Test"
            }
        }

        stage('Integration') {
            steps {
                echo "Integration"
            }
        }
    } post {
        always {
            echo "Finished"
        }
        success {
            echo "Successful build"
        }
        failure {
            echo "Failure to build"
        }
    }
}
