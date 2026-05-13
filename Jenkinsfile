pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'main', \
                url: 'https://github.com/username/sample-cicd-project.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running Tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Application...'
            }
        }
    }
}
