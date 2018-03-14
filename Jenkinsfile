pipeline {
  agent any
  stages {
    stage('t2') {
      parallel {
        stage('t2') {
          steps {
            git(url: 'https://gitee.com/sttp/sttp-facade-parent.git', branch: 'develop', credentialsId: '029c5218-d91c-4669-af5c-733153b14bf1')
          }
        }
        stage('error') {
          steps {
            echo 'hahah'
          }
        }
      }
    }
  }
}