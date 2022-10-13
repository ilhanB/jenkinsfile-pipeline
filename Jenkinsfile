pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Clarusway_Way to Reinvent Yourself"
                sh 'echo Integrating Jenkins Pipeline with GitHub Webhook using Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
        stage('test1') {
            steps {
                echo "Hello world"
            }
        }
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python --version'
                sh 'python hello-world.py'
            }
        }
	stage('test2') {
            steps {
                echo "Goodbye world"
            }
        }        
        stage('deploy') {
            steps {
                echo "this is deploy stage"
            }
        }
    }
}
