pipeline {
    agent any
    environment { 
        CC = 'clang'
    }
    stages {
        stage('Test') {
            environment { 
                AN_ACCESS_KEY = "int"
            }
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
                sh 'printenv'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploying app..."'
                sh 'printenv'
            }
        }
    }
}
