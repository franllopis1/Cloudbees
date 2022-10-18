@Library('shared-library') _
pipeline {
    agent { label 'java' }
    stages {
        stage('verify') {
            steps {
                helloWorld(name: 'fred')
            }
        }
    }
}