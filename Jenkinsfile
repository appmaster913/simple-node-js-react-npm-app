pipeline {
    agent any
    tools {
        nodejs 'Node 18'  // or whatever name you gave it
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
