pipeline {
  agent {
    label 'master'
  }
  stages {
    stage('deploy') {
      steps {
        echo 'Start Pull And Push Images'
        sh 'git clone git@github.com:reyhsu/docker-gitlab.git'
        sh 'cat ababwer >> new.txt; cp new.txt sec.txt'
      }
    }
  }
}