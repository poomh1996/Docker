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
				  sh "chmod -R 777 index.html"
				 sh "docker stop server"
				 sh" docker rm server"
				  sh " docker run -itdp 80:80 --name server httpd"
				 sh "docker cp Docker/index.html server:/usr/local/apache2/htdocs"
				
				  
				  
				  }
				 }
				}
				  
				  

			  
	         








}
