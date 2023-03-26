pipeline{
        agent{
               label{
                label'built-in'
				customWorkspace'/mnt/docker'
              }
			 } 
		stages{
		     
			 stage('container-1'){
			 steps{
				 sh "rm -rf *"
			         sh "git clone https://github.com/poomh1996/Docker.git"
				 sh " docker run -itdp 80:80 --name server1 httpd"
				 sh "docker cp Docker/index.html server1:/usr/local/apache2/htdocs"
				
				  
				  
				  }
				 }
				}
				  
				  

			  
	         








}
