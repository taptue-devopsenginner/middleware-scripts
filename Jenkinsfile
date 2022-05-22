pipeline {
    agent any

    stages {
        stage('pull-from-git') {
            steps {
                echo 'Hello'
                sleep 12
            }
        }
        stage('Building') {
            steps {
                echo 'Build'
                sleep 12
            }
        }
        stage('Testing') {
            steps {
                echo 'Test'
                sleep 12
            }
        }
        stage('artifact-created') {
            steps {
                echo 'Deployment'
                sleep 12
            }
        }
        stage('upload-artifact') {
            steps {
                echo 'artifact has been create'
                sleep 12
                
            }
        }
    }
}
