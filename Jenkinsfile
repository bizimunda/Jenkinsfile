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
    }
}

