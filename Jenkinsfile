pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploying app..."'
            }
        }
    }
}
