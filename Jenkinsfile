pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "hi"
                python test.py
            }
        }
        stage('Test') { 
            steps {
            echoo "hello"
            }
        }
        stage('Deploy') { 
            steps {
                echo "hi-2"
            }
        }
    }
}
