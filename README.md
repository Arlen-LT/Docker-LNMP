# Docker-LNMP  
### The PHP ***"Dockerfile"*** is used to pre-build a php image with the extensions required in the future. If you use an official php image, once you need the extensions, you can use command ***docker exec -it <Container_ID> bash*** to install the extensions for one time.  
### The mail ***"Dockerfile"*** is an image including exim4 and dovecot. It can work well as your mail server.  
### The file ***"docker-compose.yml"*** is used to control the containers related to your website. The most important thing is ***Database volumes***.
