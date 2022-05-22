pipeline {
    agent any

    stages {
        stage('pull-from-git') {
            steps {
                echo 'Hello'
                sleep 10
            }
        }
        stage('Building') {
            steps {
                echo 'Build'
                sleep 10
            }
        }
        stage('Testing') {
            steps {
                echo 'Test'
                sleep 10
            }
        }
        stage('artifact-created') {
            steps {
                echo 'Deployment'
                sleep 10
            }
        }
        stage('upload-artifact') {
            steps {
                echo 'artifact has been create'
                sleep 10
                
            }
        }
    }
}
