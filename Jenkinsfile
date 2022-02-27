pipeline {
    agent any

    stages{
        stage('ssh to LEMP server'){
            steps{
               sh 'ssh ubuntu@34.205.159.237'
		     sh 'touch file.txt'
		     sh 'sudo -S nginx -t'
		    sh 'sudo -S systemctl restart nginx'   
            	}
        }
	
    }
    
}
