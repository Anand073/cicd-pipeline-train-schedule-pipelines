pipeline {
  agent any
  stages {
     stage('Build') {
       steps {
          echo "I am running build automation"
          sh './gradlew build --no-daemon'
          archiveArtifacts artifacts: 'dist/trainSchedule.zip'
       }
      
     }
  }
}
