@Library('sharedlib@main') _
pipeline {
    agent any
    stages {
        stage('Test Shared Lib') {
            steps {
                script {
                    myLog("This is a test log from the shared library")
                }
            }
        }
    }
}
