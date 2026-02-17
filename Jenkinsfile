pipeline {
    agent any

    tools {
        maven 'Maven-3'
    }

    stages {
        stage('Compilar Proyecto') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}

