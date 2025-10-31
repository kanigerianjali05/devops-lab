pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/kanigerianjali05/devops-lab.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project…'
                // add build commands here (e.g., for Java: mvn clean install)
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests…'
                // add test commands
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying…'
                // add deployment commands (optional)
            }
        }
    }
}
