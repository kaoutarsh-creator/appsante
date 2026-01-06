pipeline {
    agent any

    stages {
        stage('Pull Code') {
    steps {
        git url: 'https://github.com/kaoutarsh-creator/appsante.git'
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
