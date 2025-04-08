pipeline {
    agent none
    stages {
        stage('Example Build') {
            agent { docker 'maven:3.9.3-eclipse-temurin-17' }
            steps {
                echo 'Hello, Maven'
                sh 'mvn --version'
            }
        }
        stage('Example Test') {
            agent { docker 'openjdk:17-jre' }
            steps {
                echo 'Hello, JDK'
                sh 'java -version'
            }
        }
    }
}
// pipeline {
//     agent any
//     environment {
//         MY_VAR='une variable'
//         USER= 'malal'
//     }

//     stages {
//         stage('Build') {
//             steps {
//                 echo 'Building..'
//                 echo "BRANCH_NAME : ${ env.BRANCH_NAME }"
//                 echo "BRANCH_IS_PRIMARY : ${ env.BRANCH_IS_PRIMARY }"
//                 echo "CI : ${ env.CI }"
//                 echo "BUILD_NUMBER : ${ env. BUILD_NUMBER }"
//                 echo "MY_VAR: ${ env.MY_VAR }"
//                 echo "USER: ${ env.USER }"
//                 sh 'printenv'
//             }
//         }
        // stage('Test') {
        //     steps {
        //         echo 'Testing..'
        //     }
        // }
        // stage('Deploy') {
        //     steps {
        //         echo 'Deploying....'
        //     }
        // }
//     }
// }