pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building on main ${env.BRANCH_NAME}"
            }
        }
        stage('Test') {
            steps {
                echo "Building feature ${env.BRANCH_NAME}"
            }
        }
    }
}
