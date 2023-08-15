pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '''
                #!/bin/bash
                echo "This is the build"
                '''
            }
        }
        
        stage('Test') {
            steps {
                sh '''
                #!/bin/bash
                echo "This is a test"
                '''
            }
        }
        
        stage('Deploy') {
            steps {
                sh '''
                #!/bin/bash
                echo "This is a deployment"
                '''
            }
        }
    }
}