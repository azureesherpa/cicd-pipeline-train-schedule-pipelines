pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo 'Running build automation '
        sh 'grawdle clean build'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }

    }

  }


}
