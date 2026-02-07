pipeline {
    agent any

    stages {

        stage('Clone Repo') {
            steps {
                echo 'Repository Cloned Automatically'
            }
        }

        stage('Check Python') {
            steps {
                bat 'python --version'
            }
        }

        stage('Run Python File') {
            steps {
                bat 'python array34.py'
            }
        }
    }
}
