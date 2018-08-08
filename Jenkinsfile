pipeline {
  agent {
    node {
      label 'jdk8'
    }

  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hi'
        sh 'java -version'
      }
    }
  }
}