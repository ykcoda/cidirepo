pipeline{
    agent any 

    stages{
        stage('Building'){
            agent {docker 'ubuntu:alphine'}
            sh 'Building.....'
        }
        stage('Testing'){
            sh 'Testing......'    
        }   

        stage('Deployment'){
            sh 'Deploying........'
        } 
    }
}