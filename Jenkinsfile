pipeline {
    agent any
     tools {
        maven 'M2_HOME'
    }
  
    stages {
        stage('Example') {
            steps {
           
                sh 'mvn --version'
            }
        }
    }
}
