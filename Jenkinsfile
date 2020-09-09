pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'building'
        retry(count: 3) {
          sh 'wwwww'
        }

      }
    }

    stage('test') {
      steps {
        echo 'testing'
        sh 'wwwwwww'
      }
    }

    stage('deploy') {
      steps {
        input(message: 'Are you sure to deploy?', ok: 'Yes')
        echo 'deploy'
        sh 'date'
      }
    }

    stage('Notify new release') {
      steps {
        echo 'new release deployed'
      }
    }

  }
}