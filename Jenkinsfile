node {  
    stage('Build') { 
        sshagent(['12345678']) {
                sh '''
                    ssh ${APP_HOST} "cd /home/appmin/; 
                    docker-compose up -d;
                    docker ps;
                "'''

}
