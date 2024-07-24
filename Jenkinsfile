pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                // Echo Hello, World!
                echo 'Hello, master branch!'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Hello, build step!'
            }
        }
        
        stage('Deploy') {
            steps {
                // Echo Hello, World!
                echo 'Hello, deploy!'
            }
        }
    }
    
    post {
        success {
            echo 'Master branch completed successfully!'
        }
        failure {
            echo 'Master branch failed!'
        }
    }
}
