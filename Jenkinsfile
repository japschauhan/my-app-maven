pipeline {
    agent any 
     tools {
    maven 'M2'
  }
    stages {
        stage('Clean') { 
            steps {
                sh "mvn clean"
            }
        }
        stage('Test') { 
            steps {
                sh "mvn test" 
            }
        }
        stage('Deploy') { 
            steps {
                sh "mvn packag"
            }
        }
    }
}
