
pipeline {
    agent any
     tools {
        maven 'apache-maven-3.5.4'
    }
  
    stages {
        stage('Example') {
            steps {
                sh 'java -version'
                sh 'mvn --version'
            }
        }
    }
}
