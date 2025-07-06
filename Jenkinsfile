pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo 'Cloning GitHub repository...'
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
