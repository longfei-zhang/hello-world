pipeline {
  agent {
    node {
      label 'build_iso'
    }

  }
  stages {
    stage('test1') {
      steps {
        echo 'test'
        sh 'echo $HOSTNAME'
      }
    }

  }
}