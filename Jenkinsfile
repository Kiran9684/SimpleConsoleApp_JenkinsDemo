pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout your source code from your repository
                git 'https://github.com/Kiran9684/SimpleConsoleApp_JenkinsDemo.git'
            }
        }
        stage('Build') {
            steps {
                // Build your console application using .NET CLI
                bat 'dotnet build'
            }
        }
    }
}