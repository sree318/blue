pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build success'
         parallel (
            "firstTask" : {
            echo 'build success1'
            },
            "secondTask" : {
               echo 'build success2'
            }
        )
      }
    }

  }
}
