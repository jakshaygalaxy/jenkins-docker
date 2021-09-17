pipeline {
    agent {
        node { label 'jenkins-slave' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
