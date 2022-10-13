pipeline {
    agent any
    tools {
        maven 'Maven-3.6.3'
        jdk 'Java 11.0.16'
    }
    stages{
        stage ('Git checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Strvsuri/USEFUL-demo-counter-app.git'
            }
        }
         stage ('Unit testing') {
            steps {
                sh 'mvn test'
            }
        }
    }
}
