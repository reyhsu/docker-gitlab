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
        stage('stage2') {
          steps {
            sh 'cp XshellPortable.rar /tmp/newlr.tar'
          }
        }
        stage('ssh ') {
          steps {
            sh 'ssh 192.168.152.17'
          }
        }
      }
    }
  }
}