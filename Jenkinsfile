pipeline{
    agent any

    stages{
        stage("VM Node Version"){
            steps{
                sh '''
                    node -v 
                    npm -v
                    hostname
                '''
                echo "hello world"
            }
        }
    }
    
}