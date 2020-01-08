pipeline {
    agent any 
    stages {
        stage('Hello') { 
            steps {
                echo 'Hello'
            }
        }
        stage('PWD') { 
            steps {
                sh 'pwd'
            }
        }
        stage('ENV') { 
            steps {
                echo env.BRANCH_NAME
            }
        }
    }
}