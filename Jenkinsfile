pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'building'
        timeout(time: 3, unit: 'SECONDS') {
          sh 'sleep 5'
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