Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'cd /Users/dulinh.lam/Documents/August_19/jenkins_test'
                sh 'python ./test.py'
            }
        }
    }
}