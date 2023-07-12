pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo 'Hello Arti'
      }
    }

    stage('clone') {
      steps {
        git(url: 'https://github.com/artikshatriya/Jenkins_training.git', branch: 'main')
      }
    }

  }
}