pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    // Checkout the code from GitHub
                    checkout scm
                    
                    // Build the project using Maven
                    sh 'mvn clean package'
                }
            }
        }
    }
}
