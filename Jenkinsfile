pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building.. .'
                sh 'cd webapp && sudo apt install npm && npm run build'
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