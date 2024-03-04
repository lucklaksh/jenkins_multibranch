pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package -Pdevelopment'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test -Pdevelopment'
            }
        }
        stage('Deploy') {
            steps {
                sh 'mvn deploy -Pdevelopment'
            }
        }
    }
}
