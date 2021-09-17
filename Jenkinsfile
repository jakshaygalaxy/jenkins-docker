pipeline {
    agent {
        node { label 'jenkins-slave' }
    }
    stages {
        stage('Test') {
        docker { image 'node:14-alpine' }
            steps {
            echo 'Hello, Maven'
            sh 'mvn --version'
            }
        }
    }
}
