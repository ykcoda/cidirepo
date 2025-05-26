pipeline{
    agent any 

    stages{
        stage('Building'){
            agent {docker 'ubuntu:alphine'}
            sh 'Building.....'
            sh 'Using scm for the first time'
        }
        stage('Testing'){
            sh 'Testing......'    
        }   

        stage('Deployment'){
            sh 'Deploying........'
        } 
    }
}
