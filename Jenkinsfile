pipeline {
    agent any
    stages{
        stage('build'){
            steps {
                sh 'mvn clean install'
            }
        }
        stage('Build docker image'){
            steps{
                script{
                    sh 'docker build -t website_v1 .'
                }
            }
        
                }
            }
        }

