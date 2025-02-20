
pipeline {
    agent any

    stages {
       
        stage('Building ') {
            steps {
                sh 'dotnet build'
            }
        }
        stage('Testing ') {
            steps {
                sh 'dotnet test'
            }
        }
        stage('PWD ') {
            steps {
                sh  'pwd'
            }
        }
    }
}
