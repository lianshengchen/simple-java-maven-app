pipeline {
    agent any

    environment{
        CC = 'clang'
    }

    stages {
        stage('Build') { 
            steps {
                sh 'printenv'
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}