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
                echo 'Building application'
            }

        }
        stage('Test') {
            steps {
                echo 'Testing application'
            }

        }
        stage('Running script') {
            steps {
                sh '''#!/bin/bash
                 echo "hello world" 
                '''
                
            }

        }
    }
}

