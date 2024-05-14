
pipeline{
    agent any
    stages{

        stage('Build'){
            
            steps{
            echo 'Building........'
             }
            
        }

        stage('Test'){
            when {
                changeset '**/*.sh'
            }
            steps{
            echo 'Testing........'
             }
            
        }


        stage('Deploy'){
            
            steps{
            echo 'Deploying........'
             }
            
        }

        
    }
}
