pipeline {
  agent any
  stages {
    stage('building stages') {
      parallel {
        stage('build') {
          steps {
            echo 'building'
          }
        }

        stage('build2') {
          steps {
            echo 'build2'
          }
        }

      }
    }

    stage('test') {
      steps {
        echo 'testing'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

  }
}