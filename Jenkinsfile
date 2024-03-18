pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                start git clone https://github.com/gravity-api/testng-java-maven.git
            }
            steps {
                start cd testng-java-maven
            }
            steps {
                start mvn -B -DskipTests clean package
            }
        }
    }
}