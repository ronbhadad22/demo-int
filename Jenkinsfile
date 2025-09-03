pipeline {
    agent any

    stages {
        stage('Build & Test in Parallel') {
            parallel {
                stage('Build') {
                    steps {
                        echo "Building the project..."
                        sh 'sleep 5 && echo Build done'
                    }
                }
                stage('Unit Tests') {
                    steps {
                        echo "Running unit tests..."
                        sh 'sleep 3 && echo Unit tests passed'
                    }
                }
                stage('Integration Tests') {
                    steps {
                        echo "Running integration tests..."
                        sh 'sleep 7 && echo Integration tests passed'
                    }
                }
            }
        }
    }
}
