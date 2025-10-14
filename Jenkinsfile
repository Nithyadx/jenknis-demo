pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        stage('Run Python Code') {
            steps {
                sh 'python3 hello.py'
            }
        }
    }
}
