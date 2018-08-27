pipeline {
  agent any
  stages {
    stage('Trigger') {
      steps {
        publishEvent(event: 'simpleEvent(\'eventTrigger\')')
      }
    }
  }
}