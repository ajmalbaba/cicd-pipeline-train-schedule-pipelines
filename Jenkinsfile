pipeline {
  agent any
  stages {
    stage ('buid') {
      steps {
        echo "running build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip
      }
    }
  }
}
