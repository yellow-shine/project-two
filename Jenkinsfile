pipeline {
  agent any
  stages {
    stage('Stage') {
      steps {
        sh """
        	echo \$CHANGE_TARGET 
        	echo \$BRANCH_NAME 
        	echo \$GIT_BRANCH 
        	echo \$GIT_URL 

        """
        // checkout scm
        // tektonCreateRaw(inputType: 'FILE', input: '.tekton/pipeline.yaml')
      }
    }
  }
}
