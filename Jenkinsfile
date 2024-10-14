pipeline {
    agent any  // Use any available Jenkins agent

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Simulate a build process
                sh 'echo "Build step complete"'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Testing the project...'
                // Simulate testing
                sh 'echo "Test step complete"'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // Simulate deployment
                sh 'echo "Deploy step complete"'
            }
        }
    }

    post {
        always {
            echo 'Cleaning up workspace...'
            cleanWs()  // Clean the workspace after the build
        }
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
 
