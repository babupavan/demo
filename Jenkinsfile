pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                // Echo Hello, World!
                echo 'Hello, World!'
            }
        }
    }
    
    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
