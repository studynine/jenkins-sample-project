pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'mvn clean install'
      }
    }

    stage('test') {
      steps {
        sh 'mvn test'
      }
    }

    stage('post-test') {
      steps {
        echo 'hey ! it worked'
      }
    }

  }
}