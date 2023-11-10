pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Desde Git"
                sh "sudo apt-get install docker"
                sh "docker ps"
            }
        }
    }
}
