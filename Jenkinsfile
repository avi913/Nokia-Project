pipeline {
    agent any

    stages {
        stage('Initialize') {
            steps {
                echo "Initializing build for branch: ${env.BRANCH_NAME}"
            }
        }

        stage('Build') {
            steps {
                echo " Building the application..."
            }
        }
    }
}
