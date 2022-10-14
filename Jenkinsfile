pipeline {
    agent any
    stages {
        stage("build"){
            steps{
                echo 'building the application.....'
            }
        }
        stage("test"){
            steps{
                echo 'testing the application......'
            }
        }
        stage("deploy"){
            steps{
                echo 'deploy the applications.......'
            }
        }
    }
    post {
        always{
            echo 'Jenkins Job Completed .....'
        }
        success {
            echo 'Jenkins Job Successfully Completed ......'
        }
        failure {
            echo 'Jenkins Job Failed for some Reason......'
        }
    }
}

