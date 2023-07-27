pipeline {
    agent any

    stages {
        stage('animated-ani') {
            steps {
                git branch: 'main', url: 'https://github.com/ChatKozak/Jenkins_assignment2.git'
            }
        }
        stage('Run Python Code') {
            steps {
                sh 'python3 hello.py'
            }
        }
        
    }
}
