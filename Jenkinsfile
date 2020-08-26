pipeline {
  agent any
 triggers {
  cron 'H/33 * * * *'
}

  stages {
    stage('echo') {
      steps {
        echo 'hello'
        sh '''chmod u+x test.sh
              ./test.sh'''
      }
    }

  }
}
