pipeline {
    agent any
    tools {
        maven 'maven 3'   // غيّر الاسم حسب Global Tools Config
        jdk   'jdk 17'    // أو الإصدار اللي بتحتاجه
    }

    stages {
        stage('compile') {
            steps {
                sh "mvn compile"
            }
        }

        stage('package') {
            steps {
                sh "mvn package"
            }
        }
    }
}
