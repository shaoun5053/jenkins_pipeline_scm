node {  
    stage('Build') { 
        sshagent(['62e832f7-b04a-4a4b-807a-c6dd92d8e2d6']) {
                sh '''
                    ssh appmin@192.168.1.231 "cd /home/appmin; 
                    docker-compose up -d;
                    docker ps;
                "'''
    }
    }
}
    
