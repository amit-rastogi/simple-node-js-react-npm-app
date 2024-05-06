pipeline {
  agent {
     dockerfile 'true'
  }

  stages {
    stage("check") {
       steps {
          sh '''
             echo "hello"
             node --version
             git --version
             curl --version
          '''
       }
    }
  }
}
