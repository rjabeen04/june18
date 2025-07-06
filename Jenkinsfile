pipeline {
    agent any


    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('List Files') {
            steps {
                echo 'Listing files in workspace:'
                sh 'ls -l'
            }
        }
        stage('Display File Content') {
            steps {
                echo 'Displaying data.txt content:'
                sh 'cat data.txt'
            }
        }
    }
}
