pipeline {
agent any
  stages('Build') {
    steps{
          echo 'running build automation'
          sh './gradlew build --no-daemon'
          archiveArtifacts artifacts: 'dist/trainShedule.zip'
    }
    
  }
}
