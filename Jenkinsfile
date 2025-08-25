@Library('sharedlib') _
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
