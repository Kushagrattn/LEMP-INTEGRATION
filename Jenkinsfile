pipeline {
    agent any

    stages{
        stage('ssh to LEMP server'){
            steps{
               sh 'ssh ubuntu@34.205.159.237'
            }
        }
	stage('Check NGINX Configuration'){
            steps{
               sh 'touch file.txt'
            }
        }
        stage('Check NGINX Configuration'){
            steps{
               sh 'sudo nginx -t'
            }
        }
        stage('Restarting the Nginx'){
        steps{
	      sh 'sudo systemctl restart nginx'        
            }
        
        }
    }
    
}
