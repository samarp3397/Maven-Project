pipeline {
    agent any
    stages {
        stage('--clean--') {
            steps {
                 bat "mvn clean verify"
            }
        }
        stage('--test--') {
            steps {
                 bat "mvn test"
            }
        }
        stage('--install--') {
            steps {
                bat "mvn install"
            }
        }
    }
}
