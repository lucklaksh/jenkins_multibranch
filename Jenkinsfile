pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh' echo "building.." '
                //sh 'mvn clean package -Pfeature'
            }
        }
        stage('Test') {
            steps {
                sh' echo "testing.." '
                //sh 'mvn test -Pfeature'
            }
        }
    }
}
