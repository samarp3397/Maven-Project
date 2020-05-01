pipeline {
    agent any
    stages {
        stage('--test--') {
            steps {
                 bat 'mvn test'
            }
        }
        stage('--package--') {
            steps {
                bat "mvn package"
            }
        }
    }
}
