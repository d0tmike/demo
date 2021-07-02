pipeline {
    agent { 
        docker { 'maven:3.8.1-openjdk-11' }
    stages {
        stage('Test') {
            steps {
                sh 'mvn -version'
            }
        }
    }
}
