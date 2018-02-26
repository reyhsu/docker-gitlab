pipeline {
  agent any
  stages {
    stage('deploy') {
      parallel {
        stage('deploy') {
          steps {
            echo 'Start Pull And Push Images'
            sh 'echo ababwer >> /new.txt; cp /new.txt /sec.txt'
            archiveArtifacts 'XshellPortable.rar'
          }
        }
        stage('error') {
          steps {
            sh 'mv XshellPortable.rar; /tmp/newlr.tar'
          }
        }
      }
    }
  }
}