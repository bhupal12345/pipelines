pipeline {
    agent any
    def mvnHome = tool name: 'maven', type: 'maven'
    def mvncmd= "$(mvnHome)/bin/mcv"

    stages {
        stage('---clean---') {
            steps {
              echo"first step1"
                "$(mvnCMD) compile"
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
