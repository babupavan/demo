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

       stage('build') {
           steps {
                echo 'Hello, builtd step!'
            }
        }
        stage('deploy') {
            steps {
                // Echo Hello, World!
                echo 'Hello, deploy'
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
