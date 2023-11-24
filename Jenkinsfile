pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh '/path/to/tsc && vite build'
                sh 'cd webapp && npm run build'
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