node {  
    stage('Build') { 
        sshagent(['12345678']) {
                sh '''
                    ssh appmin "cd /home/appmin; 
                    docker-compose up -d;
                    docker ps;
                "'''
    }
    }
}
    
