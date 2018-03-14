pipeline {
  agent any
  stages {
    stage('t2') {
      parallel {
        stage('t2') {
          steps {
            git(url: 'https://gitee.com/sttp/sttp-facade-parent.git', branch: 'develop')
          }
        }
        stage('') {
          steps {
            echo 'hahah'
          }
        }
      }
    }
  }
}