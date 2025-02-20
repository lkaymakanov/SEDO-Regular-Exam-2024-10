
pipeline {
    agent any

    stages {
       
        stage('Building ') {
            steps {
                bat 'dotnet build'
            }
        }
        stage('Testing ') {
            steps {
                bat 'dotnet test'
            }
        }
        stage('PWD ') {
            steps {
                echo  'cd'
            }
        }
    }
}
