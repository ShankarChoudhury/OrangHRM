pipeline {
    agent any 
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello, Maven'
                withMaven(maven : 'myMaven') {
                    bat 'mvn clean'
                }
            }
        }
        stage('Example Test') {
            steps {
                echo 'Hello, JDK'
               
            }
        }
    }
}
