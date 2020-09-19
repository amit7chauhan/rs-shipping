pipeline {
    agent any

    tools {
        maven 'maven-3.6.3'
        java 'java-8.221'
    }

    stages {
        stage('Compile code') {
            steps {
                sh '''
                    mvn compile
                '''
            }

        }

    }

}