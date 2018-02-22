pipeline {
  agent {
    node {
      label 'CCU_Slave_test'
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