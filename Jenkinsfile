pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh "bash ./hello.sh"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..With..github..KS'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
