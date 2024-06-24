pipeline{
    agent any 
    // agent {
    //     docker {
    //         image 'node:21-alpine'
    //     }
    // }
    options {
        timeout(time: 1, unit: "HOURS")
    }
//    agent any
   environment {
     MY_VAR= 'ya'
     MY_NUMBER= 123
     DALABA='BELLE'
   }
   parameters {
     string(name: 'NAME', defaultValue: 'Mr DIALLO', description: 'Qui est ce ?')
     text(name: 'TEXT', defaultValue: 'un text', description: 'Une description ?')
     booleanParam(name: 'TOGGLE', defaultValue: true, description: 'trur ou false')
     choice(name: 'CHOICE', choices:[ 'un', 'deux', 'trois'], description: 'liste ')
     password(name: 'PASSWORD', description: 'un mot de passe')
   }

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
            echo "NAME: ${NAME}"
            echo "TEXT: ${TEXT}"
            echo "TOGGLE: ${TOGGLE}"
            echo "CHOICE: ${CHOICE}"
            echo "PASSWORD: ${PASSWORD}"
        }
      }
   }
   post {
    always {
        echo 'always'
    }
    success {
        echo 'succes'
    }
   }
