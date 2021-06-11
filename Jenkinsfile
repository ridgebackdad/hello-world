pipeline {
  agent any
  stages {
    stage('part 1') {
      steps {
        echo 'Starting'
      }
    }

    stage('error') {
      steps {
        git(url: 'https://github.com/ridgebackdad/hello-world.git', branch: 'Master')
      }
    }

  }
}