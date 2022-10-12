pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Clarusway_Way to Reinvent Yourself"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
        stage('test') {
            steps {
                echo "Hello world"
            }
        }
        stage('deploy') {
            steps {
                echo "this is deploy stage"
            }
        }
    }
}
