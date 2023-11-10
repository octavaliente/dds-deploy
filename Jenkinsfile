pipeline {
    agent any
    stages {
        stage('Config') {
            steps {
                echo "Etapa de Configuracion"
            }
        }
        stage('Scan') {
            steps {
                echo "Etapa de SonarQube"
            }
        }
        stage('Test') {
            steps {
                echo "Etapa de Test"
            }
        }
        stage('Deploy') {
            steps {
                echo "Etapa de Deploy a Minikube"
            }
        }
    }
}
