pipeline {
    agent any

    stages {
        stage('Build') { 
            steps {
                sh 'printenv'
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}