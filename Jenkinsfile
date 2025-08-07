 pipeline {
        agent any

        stages {
            stage('Build') {
                steps {
                    echo 'application building...'
                    sh 'python3 hello.py'
                }
            }
            stage('Test') {
                steps {
                      sh 'python3 hello.py'
                      echo 'Running tests...'
                    
                }
            }
            stage('Deploy') {
                steps {
                    sh 'python3 hello.py'
                    echo 'Deploying the application...'
                    // Add your deployment commands here
                }
            }
        }
    }
