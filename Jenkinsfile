pipeline {
  agent any
  stages {
    stage('Trigger') {
      steps {
        publishEvent(event: '{event:"generic://eventName"}')
      }
    }
  }
}