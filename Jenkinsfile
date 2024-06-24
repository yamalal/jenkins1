pipeline{
   agent any

   stages {
      stage('build') {
        steps{
            echo "BRANCH_NAME: ${env.BRANCH_NAME}"
            echo "EXECUTOR_NUMBER: ${env.EXECUTOR_NUMBER}"
            echo "BUILD_TAG: ${env.BUILD_TAG}"
            echo "JENKINS_URL: ${env.JENKINS_URL}"
            echo "JOB_BASE_NAME: ${env.JOB_BASE_NAME}"
        }
      }
   }
}