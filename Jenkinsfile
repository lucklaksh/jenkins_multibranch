pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "testing here.."
                //sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "deploying here.. "
                //sh 'mvn deploy'
            }
        }
    }
}
