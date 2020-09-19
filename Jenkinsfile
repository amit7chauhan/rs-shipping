pipeline {
    agent any

    tools {
        maven 'maven-3.6.3'
        jdk 'java-8.221'
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

     stages {
            stage('Package Code') {
                steps {
                    sh '''
                        mvn package
                    '''
                }

            }

        }

}