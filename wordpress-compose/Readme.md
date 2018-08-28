DOCKER-COMPOSE WORDPRESS SET UP




  Created wordpress directoy:
                             
                             in this directory created docker-compose.yml
    
    
   On the wordpress directory create shared voulme directory:
                                
                                nginx --for customise wordpress.conf file
                                
                                
                                wordpress -- for php files customizaytion
                                
                                db-data  --for mysql customizations
                                
                                logs/nginx  -- for nginx webserver logs
                                
 Docker-compose up --to up the all conatiners.
 
 
    TO check all the containers running or not:
                                               docker ps  --to check which containers are running
                                               netstat -ntlp  --to check which ports are listening
 
 We can see the logs from output from the container
 
 docker-compose logs mysql
 
 We can login into any our conatiners
 
 docker-compose exec nginx bash
 
     
