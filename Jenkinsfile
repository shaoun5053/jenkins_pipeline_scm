node {  
    stage('Build') { 
        sshagent(['a8183634-00cb-40f6-8547-0c18ac5c3d17']) {
                sh '''
                    ssh appmin@192.168.1.253 "cd /home/appmin; 
                    docker-compose up -d;
                    docker ps;
                "'''
    }
    }
}
    
