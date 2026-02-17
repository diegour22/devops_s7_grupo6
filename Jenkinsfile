pipeline {
    agent any

    tools {
        maven 'Maven-3'
    }

    stages {
        stage('Compilar') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}


