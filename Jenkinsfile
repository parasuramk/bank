pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        withSonarQubeEnv(installationName: 'My SonarQube Server', credentialsId: '4a7a7580f06c96ce02fe78462c745a0face97ee7')
      }
    }

  }
}