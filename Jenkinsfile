pipeline{
   agent any
   environment {
     MY_VAR= 'ya'
     MY_NUMBER= 123
     DALABA='BELLE'
   }

   stages {
      stage('build') {
        steps{
            echo "BRANCH_NAME: ${env.BRANCH_NAME}"
            echo "EXECUTOR_NUMBER: ${env.EXECUTOR_NUMBER}"
            echo "BUILD_TAG: ${env.BUILD_TAG}"
            echo "JENKINS_URL: ${env.JENKINS_URL}"
            echo "JOB_BASE_NAME: ${env.JOB_BASE_NAME}"
            echo "MY_VAR: ${env.MY_VAR}"
            echo "MY_NUMBER: ${env.MY_NUMBER}"
            // sh "printenv"
            echo "DALABA: ${env.DALABA}"
        }
      }
   }
}