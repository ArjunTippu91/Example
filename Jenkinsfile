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
                echo 'Testing..With..github..RAKS-MPL1'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
