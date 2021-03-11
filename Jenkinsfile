pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                chmod 777 ./hello.sh
                sh ./hello.sh
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
