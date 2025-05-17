pipeline {
    agent {
        label 'docker' // MUST MATCH your Docker Template's label
    }
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
