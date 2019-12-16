pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        s3Upload(bucket: 'dtcc-jenkins-poc', workingDir: '/')
      }
    }

  }
}