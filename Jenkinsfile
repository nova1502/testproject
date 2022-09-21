pipeline {
     agent any
     tools {
         jdk "java11"
     }
     stage {
         stage('Build') {
             steps {
                 sh 'javac hello.java'
                 sh 'java hello'
             }
         }
     }
}
