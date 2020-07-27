pipeline {
    agent any
    stage("Adding Node") {
    node("logreader") {
        echo "Node added"
    }
}
    stages {
        stage('Run file') { 
            steps {
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
