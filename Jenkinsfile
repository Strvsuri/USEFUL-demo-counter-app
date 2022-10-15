pipeline {
    agent any
    stages{
        stage ('Git checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Strvsuri/USEFUL-demo-counter-app.git'
            }
        }
        stage ('Unit testing') {
            steps {
                echo "mvn -version"
            }
        }       
    }
}
