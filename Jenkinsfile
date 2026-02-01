pipeline {
    agent {
        label 'ubuntus-agent' 
    }
    
    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code from repository'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Building the application'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Running tests'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying the application'
            }
        }
    }
}
