pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building College Website'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing College Website'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying College Website'
            }
        }
    }
}
