pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo 'Running build automation '
        sh './grawdlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }

    }

  }


}
