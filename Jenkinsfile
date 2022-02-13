pipeline {
    agent { docker { image 'golang:1.17.5-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
        stage('test') {
            steps {
                sh 'echo Hello World'
            }
        }
    }
}
