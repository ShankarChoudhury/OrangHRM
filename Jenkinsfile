pipeline {
    agent any 
    stages {
        stage('Example Build') {
            agent { docker 'maven:3-alpine' } 
            steps {
                echo 'Hello, Maven'
                sh 'mvn --version'
            }
        }
        stage('Example Test') {
            steps {
                echo 'Hello, JDK'
                sh 'java -version'
            }
        }
    }
}