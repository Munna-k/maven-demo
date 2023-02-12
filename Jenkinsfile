pipeline {
    agent any
    tools {
        maven 'maven'
    }
    stages{
        stage('Build') {
            steps{
                sh 'mvn clean install'
            }
        }
        stage('test') {
            steps {
                echo "testing"
            }
        }
        stage('deploying') {
            steps {
                echo "deploying"
            }
        }
    }
}