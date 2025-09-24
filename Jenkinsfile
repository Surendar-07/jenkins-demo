pipeline {
    agent any
    tools {
        maven 'Maven3'     // Name must match Global Tool Config
        jdk 'JDK21'        // Name must match Global Tool Config
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn -version'
                bat 'mvn clean install'
            }
        }
    }
}
