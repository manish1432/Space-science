pipeline {
    agent any

    stages {
        stage('Test Stage') {
            steps {
                echo 'Hello, this is a simple Jenkins Pipeline test!'
            }
        }
    }

    post {
        success {
            echo 'Pipeline executed successfully!'
        }
        failure {
            echo 'Pipeline execution failed!'
        }
    }
}
