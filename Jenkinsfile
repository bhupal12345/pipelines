








pipeline {
    agent any

   
 

    
    
    stages {
        stage('---clean---') {
            steps {
           
sh "scp target/*txt ec2-user@3.8.8.65:/home/ec2-user""
              
                
            }
        }
        stage('--test--') {
            steps {
               echo"first step1"
            }
        }
        stage('--package--') {
            steps {
              echo"first step2"
            }
        }
    }
}
