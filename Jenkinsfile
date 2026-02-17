pipeline {
    agent any

    tools {
        maven 'Maven-3'
    }

    stages {

        stage('Clonar repositorio') {
            steps {
                echo 'Clonando repositorio...'
            }
        }

        stage('Compilar proyecto') {
            steps {
                echo 'Ejecutando Maven clean package'
                sh 'mvn clean package'
            }
        }

        stage('Verificar artefacto') {
            steps {
                echo 'Verificando archivo WAR generado'
                sh 'ls -l target'
            }
        }
    }
}

