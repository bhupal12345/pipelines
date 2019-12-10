pipeline {
    agent any
    def mvnHome = tool name: 'maven', type: 'maven'
    

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
