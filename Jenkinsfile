pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                start mvn -B -DskipTests clean package
            }
        }
    }
}