pipeline {
    agent {label 'logreader'}
    stages {
        stage('Run file') { 
            steps {
                sh "docker-compose up -d"
            }
        }
        stage('Message') { 
            steps {
                sh "echo 'File installed!'"
            }
        }
        stage('Status List') { 
            steps {
                sh "docker ps"
            }
        }
    }
}
