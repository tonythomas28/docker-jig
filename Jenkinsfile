pipeline {
  agent any
  stages {
    stage('UI') {
      parallel {
        stage('Step1') {
          steps {
            git 'git@github.com:tonythomas28/docker-jig.git'
            echo 'Step1'
          }
        }

        stage('Step2') {
          steps {
            echo 'Step2'
          }
        }

      }
    }

    stage('Hello') {
      steps {
        echo 'Hello World'
      }
    }

  }
}