pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'master', \
                url: 'https://github.com/Arundhuti-Deka/git-demo.git'
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
