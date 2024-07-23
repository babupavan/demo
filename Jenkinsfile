pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                // Echo Hello, World!
                echo 'Hello, this is feature branch'
            }
        }
    }
    
    post {
        success {
            echo 'feature completed successfully!'
        }
        failure {
            echo 'feature failed!'
        }
    }
}
