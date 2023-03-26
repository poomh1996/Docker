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
			      sh "git clone https://github.com/poomh1996/vel-app2.git"
				  sh " docker run -itdp 80:80 --name server httpd"
				  sh " docker cp index.html server:/usr/local/apache2/htdocs
				  
				  }
				 }
				}
				  
				  

			  
	         








}
