pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh './script.bash'   // לדוגמה אם יש לך סקריפט לבנייה
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploying app..."'
            }
        }
    }
}
