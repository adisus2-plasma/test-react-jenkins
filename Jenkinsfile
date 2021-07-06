pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'sudo bash ./build.sh'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}