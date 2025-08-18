pipeline {
    agent any
    environment { 
        CC = 'clang'
    }
    stages {
        stage('Test') {
            environment { 
                CC = "int-tet"
            }
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
                sh 'printenv'
            }
        }

        stage('Deploy') {
            environment { 
                AN_ACCESS_KEY = "int-deploy"
            }
            steps {
                sh 'echo "Deploying app..."'
                sh 'printenv'
            }
        }
    }
}
