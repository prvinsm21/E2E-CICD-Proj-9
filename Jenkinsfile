pipeline {
    agent any
    tools {
        jdk 'jdk11'
        maven 'maven3'
    }
    environment{
        DOCKERHUB_USERNAME = "prvinsm21"
        DOCKERHUB_CREDENTIALS = credentials('dockerhub')
        DOCKERIMAGE_NAME = "prvinsm21/hostit-site:${BUILD_NUMBER}"
    }

    stages {
        stage ('Git Checkout') {
            steps {
                sh 'echo Passed'
            }
        }

        stage ('Build Stage') {
            steps {
                script {
                    
                }
            }
        }
    }

}