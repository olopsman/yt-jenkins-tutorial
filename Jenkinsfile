pipeline {
    agent any 
    stages {
        stage('build') {
            steps {
                bat 'ant -version'
            }
        }
        stage('test') {
             steps {
                bat 'java -version'
            }            
        }
        stage('deploy'){
            steps {
                bat 'node -v'
            }        
        }
    }
}
