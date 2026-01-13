pipeline{
    agent any

    stages{
        stage('Build'){
            steps{
                bat 'javac src\\HelloWorld.java'
            }
        }
        stage('Run'){
            steps{
                bat 'java -cp src HelloWorld'
            }
        }
    }
}