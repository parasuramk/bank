pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh '''sonar-scanner \\
  -Dsonar.projectKey=modelbank \\
  -Dsonar.sources=. \\
  -Dsonar.host.url=http://localhost:9000 \\
  -Dsonar.login=4a7a7580f06c96ce02fe78462c745a0face97ee7'''
      }
    }

  }
}