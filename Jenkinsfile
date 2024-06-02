
pipeline{
    agent any
    stages{


        
        stage('Build'){
            
            steps{
            echo 'Building........'
            sh 'chmod 700 hello.sh'
            sh 'ls -l'
            sh './hello.sh'
             }
            
        }

            stage('Test'){
            
            steps{
            echo 'Testing........'
           
             }
            
        }

       
        
    }
}
