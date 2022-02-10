pipeline {
  agent any
  stages {
    stage- ('Biuld') {
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archieveArtifacts artifacts: 'dis/trainSchedule.zip'
      }
    }
  }
}
