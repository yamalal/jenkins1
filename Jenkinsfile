pipeline{
  agent any
  tools {
    gradle 'gradle8.9'
  }
  stages {
    stage('build') {
      steps {
        sh 'gradle -v'
      //  sh 'echo hello > toto.txt'
      //  archiveArtifacts(artifacts: '*.txt')
      }
    }
  //   stage('build and test') {
  //     matrix {
  //       axes {
  //         axis {
  //           name'PLATFORM'
  //           values 'linux', 'macos', 'windows'
  //         }
  //         axis {
  //           name 'BROWSER'
  //           values 'firefox','chrome','safari'
  //         }
  //       }
  //       stages {
  //         stage('Build') {
  //           steps {
  //             echo "construire pour ${PLATFORM} - ${BROWSER}"
  //           }
  //         }
  //         stage('test') {
  //           steps {
  //              echo "test pour ${PLATFORM} - ${BROWSER}"
  //           }
  //         }
  //       }
        
  //     }
  //   }

  }

}


    // agent any 
    // agent {
    //     docker {
    //         image 'node:21-alpine'
    //     }
    // }
//     options {
//         timeout(time: 1, unit: "HOURS")
//     }
// //    agent any
//    environment {
//      MY_VAR= 'ya'
//      MY_NUMBER= 123
//      DALABA='BELLE'
//      DEPLOY_TO='production'
//    }
//    parameters {
//      string(name: 'NAME', defaultValue: 'Mr DIALLO', description: 'Qui est ce ?')
//      text(name: 'TEXT', defaultValue: 'un text', description: 'Une description ?')
//      booleanParam(name: 'TOGGLE', defaultValue: true, description: 'trur ou false')
//      choice(name: 'CHOICE', choices:[ 'un', 'deux', 'trois'], description: 'liste ')
//      password(name: 'PASSWORD', description: 'un mot de passe')
//    }

//    triggers {
//     cron('* * * * *')
//    }
  //    triggers {
  //       pollSCM('* * * * *')
  //    }
  //  stages {
  //     stage('build') {
  //       steps{
            // echo "BRANCH_NAME: ${env.BRANCH_NAME}"
            // echo "EXECUTOR_NUMBER: ${env.EXECUTOR_NUMBER}"
            // echo "BUILD_TAG: ${env.BUILD_TAG}"
            // echo "JENKINS_URL: ${env.JENKINS_URL}"
            // echo "JOB_BASE_NAME: ${env.JOB_BASE_NAME}"
            // echo "MY_VAR: ${env.MY_VAR}"
            // echo "MY_NUMBER: ${env.MY_NUMBER}"
            // // sh "printenv"
            // echo "DALABA: ${env.DALABA}"
            // echo "NAME: ${NAME}"
            // echo "TEXT: ${TEXT}"
            // echo "TOGGLE: ${TOGGLE}"
            // echo "CHOICE: ${CHOICE}"
            // echo "PASSWORD: ${PASSWORD}"
      //   }
      // }

      // stage('deployment en production') {
      //   // input {
        //   message 'Voulez vous deployez en production ?'
        //   ok 'deployer!'
        //   submitter 'admin,devops'
        //   submitterParameter 'USER_SUBMIT'
        //   parameters{
        //     string(name: 'VERSION', defaultValue: 'latest', description: 'Une version?')
        // //   }
        // }
        // when {
        //   allOf {
        //     branch'main'
        //     environment name: 'DEPLOY_TO', value: 'production'
        // }
        // }
        // steps {
          // echo "user: ${USER_SUBMIT}"
          // echo "version: ${VERSION}"
          // echo 'deploy !'
//           }
//         }
//       }
//    post {
//     always {
//         echo 'always'
//     }
//     success {
//         echo 'succes'
//     }
//    }
// }  
