@Library ('shared-jenkins')_

pipeline {
    agent any
    
    tools {
        jdk 'jdk17'
        maven 'maven3'
    }

    stages {
        stage('Git Checkout') {
            steps {
                git 'https://github.com/Shyam2906/secretsanta-generator.git'
            }
        }
        
        stage('Build') {
            steps {
                script {
                    function('Shyam')
                    package111()
                }
            }
        }
    }
}
