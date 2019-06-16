pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo 'Running build automation '
        sh 'gradle clean build'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }

    }

  }


}
