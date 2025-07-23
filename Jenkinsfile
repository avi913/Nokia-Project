pipeline {
    agent any

    stages {
        stage('Initialize git repo') {
            steps {
                echo "Initializing build for branch from the: ${env.BRANCH_NAME}"
            }
        }

        stage('Build') {
            steps {
                echo " Building the application from multibranch"
            }
        }
    }
}
