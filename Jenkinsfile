pipeline {
    agent any
    stages {
        stage('--validate--') {
            steps {
                 bat "mvn validate"
            }
        }
        stage('--compile--') {
            steps {
                 bat "mvn compile"
            }
        }
        stage('--test--') {
            steps {
                bat "mvn test"
            }
        }
        stage('--package--') {
            steps {
                bat "mvn package"
            }
        }
       
    }
}
