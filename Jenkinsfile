pipeline {
    agent {
        label 'docker'
    }
    stages {
        stage('build') {
            agent {
                docker {
                    // Set both label and image
                    label 'docker'
                    image 'golang:1.17.5-alpine'
                }
            }
            steps {
                sh 'go version'
            }
        }
    }
}
