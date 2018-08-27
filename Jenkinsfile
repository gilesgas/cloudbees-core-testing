pipeline {
  agent any
  stages {
    stage('Trigger') {
      steps {
        publishEvent(event: 'generic://eventTrigger')
      }
    }
  }
}