pipeline {
  agent {
     label 'jenkins-controller-agent'
     dockerfile 'true'
  }

  stages {
    stage("check") {
       steps {
          sh '''
             node --version
             git --version
             curl --version
          '''
       }
    }
  }
}
