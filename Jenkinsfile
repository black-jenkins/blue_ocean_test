pipeline {
  agent any
  stages {
    stage('Example') {
      steps {
        echo '"Hello ${params.PERSON}"'
      }
    }
  }
  parameters {
    string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
  }
}