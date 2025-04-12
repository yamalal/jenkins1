pipeline {
    agent any

    stages {
        stage('build') {
           steps {
              sh 'echo hello malal > hello.txt'
              archiveArtifacts(artifacts: '*.txt')

           } 
        }
    }
}
// pipeline {
//     agent any
//     environment {
//         MY_VAR = 'une variable'
//         USER = 'malal'
//         DEPLOY_TO = 'Production'
//     }

//     stages {
//         stage('Build and test') {
//             matrix {
//                 axes {
//                     axis {
//                         name 'PLATFORM'
//                         values 'linux', 'macos', 'windows'
//                     }
//                     axis {
//                         name 'BROWSER'
//                         values 'chrome', 'edge', 'firefox'
//                     }
//                 }
//                 stages {
//                     stage('Build') {
//                         steps {
//                             echo "construire pour ${PLATFORM} - ${BROWSER}"
//                         }
//                     }
//                     stage('Test') {
//                         steps {
//                             echo "test pour ${PLATFORM} - ${BROWSER}"
//                         }
//                     }
//                 }
//             }
//         }
        
//         stage('Deployment to the production') {
//             when {
//                 allOf {
//                     branch 'main'
//                     environment name: 'DEPLOY_TO', value: 'Production'
//                 }
//             }
//             steps {
//                 echo 'Deploying....'
//             }
//         }
//     }
// }// pipeline {
//     agent none
//     stages {
//         stage('Example Build') {
//             agent { docker 'maven:3.9.3-eclipse-temurin-17' }
//             steps {
//                 echo 'Hello, Maven'
//                 sh 'mvn --version'
//             }
//         }
//         stage('Example Test') {
//             agent { docker 'openjdk:17-jre' }
//             steps {
//                 echo 'Hello, JDK'
//                 sh 'java -version'
//             }
//         }
//     }
// }
// pipeline {
//     agent any
    // environment {
    //     MY_VAR='une variable'
    //     USER= 'malal'
    //     DEPLOY_TO='Production'
    // }
    // triggers {
    //     // cron ('* * * * *')
    //     pollSCM ('* * * * *')
    // }
    // parameters {
    //     string(name: 'NAME', defaultValue: 'Malal', description: 'Qui est ce ?')
    //     text(name: 'TEXT', defaultValue: 'text', description: 'une description')
    //     booleanParam(name: 'TOGGLE',defaultValue: true, description: 'true or false' )
    //     choice(name: 'CHOICE', choices: ['un', 'deux', 'trois'], description: 'liste')
    //     password(name: 'PASSWORD', description: 'un mot de passe')

    // }
   
        //     steps {
        //         echo 'Building..'
        //         echo "BRANCH_NAME : ${ env.BRANCH_NAME }"
        //         echo "BRANCH_IS_PRIMARY : ${ env.BRANCH_IS_PRIMARY }"
        //         echo "CI : ${ env.CI }"
        //         echo "BUILD_NUMBER : ${ env. BUILD_NUMBER }"
        //         echo "MY_VAR: ${ env.MY_VAR }"
        //         echo "USER: ${ env.USER }"
        //         sh 'printenv'
        //     }
        // }
        // stage('Test') {
        //     steps {
        //         echo " le nom est : NAME ${ NAME }"
        //         echo " le text vaut : TEXT ${ TEXT }"
        //         echo " TOGGLE : ${ TOGGLE }"
        //         echo " CHOICE : ${ CHOICE }"
        //         echo ' PASSWORD: ${ PASSWORD }'
        //     }
        // }
//         stage('Deployment to the production') {
//             when {
//                 allOf {
//                     branch 'main'
//                     environment name: 'DEPLOY_TO', value: 'Production'

//                 }
                
//             }
//             // input {
//             //     message ' Voulez vous deployez en production ?'
//             //     ok ' deployer !'
//             //     submitter 'admin,DevOps'
//             //     submitterParameter 'USER_SUMITTER'
//             //     parameters {
//             //         string(name: 'VERSION', defaultValue: 'latest', description: 'une version')
//             //     }

//             // }
//             steps {
//                 echo 'Deploying....'
//                 // echo "l'utilisateur qui deploie : USER_SUMITTER ${ USER_SUMITTER }"
//                 // echo " la version de l'application: VERSION ${VERSION} "
//             }
//         }
//     }
// }