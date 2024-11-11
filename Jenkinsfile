pipeline {
  agent any
  options {
      disableConcurrentBuilds(abortPrevious: env.CHANGE_ID != null)
  }
  stages {
    stage('Stage') {
      steps {
        sh """
        sleep 10
          env

        """
        // checkout scm
        // tektonCreateRaw(inputType: 'FILE', input: '.tekton/pipeline.yaml')
      }
    }
  }
}
