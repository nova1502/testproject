pipeline {
    agent any
    tools {
        jdk "java11"
    }
    stages {
        stage('Build') {
            steps {
                sh 'javac hello.java'
                sh 'java hello'
            }
        }
    }
}
