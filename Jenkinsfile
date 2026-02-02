pipeline {
    agent any

    stages {

        stage('Welcome') {
            steps {
                echo 'Pipeline started successfully'
            }
        }

        stage('Show Files') {
            steps {
                sh 'ls'
                sh 'cat hello.txt'
            }
        }

        stage('Finish') {
            steps {
                echo 'Pipeline finished'
            }
        }
    }
}
