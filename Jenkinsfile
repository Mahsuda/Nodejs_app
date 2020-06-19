pipeline {
  agent any
  stages {
    stage('Build job') {
      steps {
        anchore(name: 'Node_app', bailOnFail: true, bailOnPluginFail: true)
      }
    }

  }
}