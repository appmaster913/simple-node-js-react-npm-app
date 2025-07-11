pipeline {
    agent any
    tools {
        nodejs 'Node 24' // this must match the name in Jenkins global tool config
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
