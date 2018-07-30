
pipeline {
    agent any
     tools {
        maven 'Apache Maven 3.5.4'
        jdk 'jdk8'
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
