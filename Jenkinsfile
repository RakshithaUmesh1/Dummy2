pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        // the git step takes named parameters; branch name must be a string
        git(
          url:  'https://github.com/RakshithaUmesh1/Dummy2.git',
          branch: 'main'
        )
      }
    }
  }
}
