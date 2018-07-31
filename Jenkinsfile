
pipeline {
    agent any
     tools {
        maven 'mvn'
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
