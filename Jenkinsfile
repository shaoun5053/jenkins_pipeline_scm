node {  
    stage('Build') { 
        sshagent(['ba6b52c8-1275-46d1-a444-e5b449673aa5']) {
                sh '''
                    ssh appmin@192.168.1.253 "cd /home/appmin; 
                    docker-compose up -d;
                    docker ps;
                "'''
    }
    }
}
    
