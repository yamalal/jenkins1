pipeline {
    agent any
    environment {
        MY_VAR='une variable'
        USER= 'malal'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo "BRANCH_NAME : ${ env.BRANCH_NAME }"
                echo "BRANCH_IS_PRIMARY : ${ env.BRANCH_IS_PRIMARY }"
                echo "CI : ${ env.CI }"
                echo "BUILD_NUMBER : ${ env. BUILD_NUMBER }"
                echo "MY_VAR: ${ env.MY_VAR }"
                echo "USER: ${ env.USER }"
                sh 'printenv'
            }
        }
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
    }
}