pipeline {
  agent any
  stage {
  stage ('Build') {
    steps  {
      echo 'Running build automation'
      sh './gradelew build --no-daemon'
      archiveArtifacts artifacts
      }
    }
  }
}
