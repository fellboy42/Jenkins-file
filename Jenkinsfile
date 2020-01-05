Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image '/home/user/entrypoi…' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}