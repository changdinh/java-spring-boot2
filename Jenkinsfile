pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                sh 'git clone https://github.com/changdinh/java-spring-boot2'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean install -f java-spring-boot2/pom.xml'
            }
        }
    }
}