pipeline {
    agent any

    stages{
        stage('ssh to LEMP server'){
            steps{
               sh 'ssh ubuntu@34.205.159.237 ; touch file.txt; echo admin | sudo -S nginx -t; echo admin | sudo -S systemctl restart nginx'
            	}
        }
	
    }
    
}
