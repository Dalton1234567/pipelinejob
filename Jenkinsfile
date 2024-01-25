pipeline {
  agent any
  stages {
    stage("copy git repo") {
      steps {
        git 'https://github.com/Dalton1234567/pipelinejob.git'
      }
    }
    stage("display readme") {
      steps {
        sh 'cat README.md'
      }
    } 
  }
}
