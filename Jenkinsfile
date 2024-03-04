pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh' echo "building.." '
                //sh 'mvn clean package -Pdevelopment'
            }
        }
        stage('Test') {
            steps {
                sh' echo "testing.." '
                //sh 'mvn test -Pdevelopment'
            }
        }
        stage('Deploy') {
            steps {
                sh' echo "deploying.." '
                //sh 'mvn deploy -Pdevelopment'
            }
        }
    }
}
