pipeline {
    agent any
    stages {
        stage('Pipeline Stages'){
            steps {
                sh "ls"
            }
        }
        stage('second stage'){
            steps {
                sh "pwd"    
            }
        }
        stage('third stage'){
            steps {
                sh "echo 'Hello World'"   
            }
        }
        stage('fourth stage'){
            steps {
                touch "text.txt"  
            }
        }
        stage('fifth stage'){
            steps {
                mv "text.txt Test.txt" 
            }
        }
}