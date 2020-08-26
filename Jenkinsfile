pipeline {
  agent any
  //
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
