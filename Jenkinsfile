pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying stage...'
            }
        }
        stage('Parallel Stage') {
            parallel {
                stage('Parallel Job 1') {
                    steps {
                        echo 'Running Parallel Job 1'
                    }
                }
                stage('Parallel Job 2') {
                    steps {
                        echo 'Running Parallel Job 2'
                    }
                }
            }
        }
    }
}
