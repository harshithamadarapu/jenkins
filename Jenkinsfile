pipeline {
    agent { label 'docker' } 
    stages {
        stage('Clone and Run') {
            steps {
                echo 'Name: Madarapu Sri Harshitha'
                echo 'Roll Number: SE22UARI087'
                sh 'python3 --version'
                sh 'echo print("Hello from Job F - Docker Cloud Agent!") > hello.py'
                sh 'python3 hello.py'
            }
        }
    }
}
