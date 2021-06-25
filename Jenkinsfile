pipeline {
  agent any
  stages {
    stage("build"){
      steps {
        echo 'testing jenkins copying files to home folder'
        fileOperations([fileCopyOperation(
          includes:*,
          targetLocation:/home
        )])
      }
    }
  }
}
