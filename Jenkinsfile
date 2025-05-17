pipeline {
    agent any // ← use this instead of label 'docker'
    stages {
        stage('Run Python') {
            steps {
                echo "Name: Madarapu Sri Harshitha"
                echo "Roll Number: SE22UARI087"
                sh 'python3 --version'
                sh 'python3 helloworld.py'
            }
        }
    }
}
