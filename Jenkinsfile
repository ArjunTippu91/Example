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
                echo 'Testing..With..github..RAKS-MPL'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
