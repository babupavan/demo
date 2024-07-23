pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                // Echo Hello, World!
                echo 'Hello, master barnch!'
            }
        }
    }
    
    post {
        success {
            echo 'master branch completed successfully!'
        }
        failure {
            echo 'master branch failed!'
        }
    }
}
