pipeline {
    agent any

    stages {
        stage('Checking Groovy Version') {
            steps {
                withGroovy{
                    sh 'groovy --version'
                }

            }

        }
        stage('Build') {
            steps {
                withGroovy{
                    echo 'Building application'
                }

            }

        }
        stage('Test') {
            steps {
                echo 'Building application'
            }

        }
    }
}

