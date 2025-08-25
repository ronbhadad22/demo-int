@Library('sharedlib@main') _
pipeline {
    agent any
    stages {
        stage('Generate Job') {
            steps {
                script {
                    myJob('example-job')
                }
            }
        }
    }
}
