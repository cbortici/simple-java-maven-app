pipeline {
    agent any
    tools {
        maven 'mvn' 
    }
    stages {
        stage('Example') {
            steps {
                sh 'mvn -v'
            }
        }
    }
}
