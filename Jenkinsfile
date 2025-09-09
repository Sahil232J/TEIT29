pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
              git branch: 'main', credentialsId: '7e7bd0e9-e1be-4610-9576-f7140af537d3', url: 'https://github.com/Sahil232J/TEIT29.git'
            }
        }
         stage('Compile') {
            steps {
            bat 'javac helloworld.java'
            }
        }
         stage('Run ') {
            steps {
            bat 'java helloworld'
            }
        }
    }
}
