pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello World - Kevin Bodie"'
                sh 'python --version'
            }
        }
    }
}
