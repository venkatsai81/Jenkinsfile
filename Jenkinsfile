
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

//The tool name must be pre-configured in Jenkins under Manage Jenkins → Global Tool Configuration.
