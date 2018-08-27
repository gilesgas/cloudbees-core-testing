pipeline {
  agent any
  stages {
    stage('Trigger') {
      steps {
        echo 'Received eventTrigger'
      }
    }
  }
  triggers {
    eventTrigger(simpleMatch('eventTrigger'))
  }
}