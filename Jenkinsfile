pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git 'https://github.com/Thesaifshaikh24/html-css-cloud-project.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building HTML project"
            }
        }

        stage('Test') {
            steps {
                echo "Testing HTML files"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying website"
            }
        }
    }
}