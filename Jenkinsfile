pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo "BRANCH_NAME : ${ env.BRANCH_NAME }"
                echo "BRANCH_IS_PRIMARY : ${ env.BRANCH_IS_PRIMARY }"
                echo "CI : ${ env.CI }"
                echo "BUILD_NUMBER : ${ env. BUILD_NUMBER }"
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