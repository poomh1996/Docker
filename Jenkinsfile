pipeline{
        agent{
               label{
                label'built-in'
				customWorkspace'/mnt/docker'
              }
			 } 
		stages{
		     
			 stage('container-3'){
			 steps{
				 sh "rm -rf *"
			         sh "git clone https://github.com/poomh1996/Docker.git"
				 sh " docker run -itdp 82:80 --name server2 httpd"
				 sh "docker cp Docker/index.html server:/usr/local/apache2/htdocs"
				
				  
				  
				  }
				 }
				}
				  
				  

			  
	         








}
