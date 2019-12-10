pipeline {
    agent any

    

    stages {
        stage('---clean---') {
            steps {
              echo"first step1"
                sh "mvn clean"
                
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
