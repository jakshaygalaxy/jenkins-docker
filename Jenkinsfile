pipeline {
    agent {
        node { label 'jenkins-slave' }
    }
    stages {
        stage('Test') {
        agent { docker 'maven:3.8.1-adoptopenjdk-11' }
            steps {
            echo 'Hello, Maven'
            sh 'mvn --version'
            }
        }
    }
}
