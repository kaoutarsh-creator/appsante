pipeline {
    agent any

    stages {
        stage('Pull Code') {
            steps {
                git 'https://github.com/username/project.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build khdam'
            }
        }

        stage('Test') {
            steps {
                echo 'Test khdam'
            }
        }
    }
}
