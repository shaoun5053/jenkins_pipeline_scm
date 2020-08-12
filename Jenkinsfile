node {  
    stage('Build') { 
        sshagent(['fb7d9626-e8cb-4b1d-bce4-0d43a2b481aa']) {
                sh '''
                    ssh appmin@192.168.1.253 "cd /home/; 
                    docker-compose up -d;
                    docker ps;
                "'''
    }
    }
}
    
