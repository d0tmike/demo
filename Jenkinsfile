pipeline {
    agent any
    tools {
        git 'git'
    }
    stages {
        stage('Build') {
            steps {
                sh 'docker build -t d0tmike/demo .'
            }
        }
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
