pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('Stage1') {
      steps {
        readFile 'FuMu_Type.txt'
      }
    }
  }
}