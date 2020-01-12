Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image '/nodered/node-red } }
    stages {
        stage('build') {
            steps {
                sh 'npm start -- --user…'
            }
        }
    }
}
