pipeline {
    agent any
    tools {nodejs 'Node.js v12.18.3'}
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
