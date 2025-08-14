pipeline {
    agent any
    tools {
        maven 'maven 3'
        jdk   'java 17'
    }
    stages {

        stage('compile') {
            steps {
                sh "mvn compile"
            }
        }

        stage('Test') {
            steps {
                sh "mvn test"

            }
        }
       stage('package') {
            steps {
                sh "mvn package "

            }
        }
        
    }
}
