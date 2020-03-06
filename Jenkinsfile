pipeline {
    agent any

    stages {
        stage('Git SCM') {
            steps {
                git 'git@github.com:yaringalmor/docker-app.git'
            }
        }
        stage('Build') {
            steps {
                echo "success"
            }
        }

    }
}