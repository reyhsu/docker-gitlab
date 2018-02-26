pipeline {
  agent {
    label 'master'
  }
  stages {
    stage('deploy') {
      parallel {
        stage('deploy') {
          steps {
            echo 'Start Pull And Push Images'
            sh 'id; pwd'
          }
        }
        stage('error') {
          steps {
            sh 'cd ~; ls -al'
          }
        }
      }
    }
  }
}