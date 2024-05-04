pipeline {
    agent any
    tools {nodejs "nodejs-20.12.2"}
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
