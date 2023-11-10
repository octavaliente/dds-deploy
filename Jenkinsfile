pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Desde Git"
                sh "yum install docker"
                sh "docker ps"
            }
        }
    }
}
