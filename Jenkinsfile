pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
 		sh  'mvn clean build'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
