pipeline {
    agent any 
    stages {
        stage("Git Checkout") {
            steps{
                script {
                    sh "Git cloning...."
                    git 'https://github.com/ashishvarshney100/Pipeline-Projects.git'
                }
            }
        }
        // stage("Code Compile") {
        //     steps{
        //         sh "Code is Compiling...."
        //     }
        // }
        // stage("Code Build") {
        //     steps{
        //         sh "Code is Building...."
        //     }
        // }
        // stage("Code Test") {
        //     steps{
        //         sh "Code testing is in progress...."
        //     }
        // }
        // stage("Code Deploy") {
        //     steps{
        //         sh "Deploying the application...."
        //     }
        // }
        // stage("Verify Deploy") {
        //     steps{
        //         sh "Verifying the Deployed Application ...."
        //     }
        // }
    }
}