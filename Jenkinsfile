pipeline {
  agent any
  stages {
    stage('build') {
      steps {
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
