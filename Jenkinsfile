pipeline {
    agent {label 'logreader'}
    stages {
        stage('Run file') { 
            steps {
                sh "sudo chmod 777 docker-compose.yml"
                sh "sudo docker-compose up -d"
            }
        }
        stage('Message') { 
            steps {
                sh "echo 'File installed!'"
            }
        }
        stage('Status List') { 
            steps {
                sh "sudo docker ps"
            }
        }
    }
}
