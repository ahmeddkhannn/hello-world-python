pipeline {
    agent any
    stages {
        stage(
Build) {
            steps {
                echo "Building the Python application..."
                sh "python3 --version"
            }
        }
        stage(Test) {
            steps {
                echo "Running tests..."
                sh "echo No tests available"
            }
        }
        stage(Deploy) {
            steps {
                echo "Deploying the application..."
                sh "echo Deployment successful"
            }
        }
    }
}
