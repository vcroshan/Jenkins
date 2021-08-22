#Install Pre-requisites

#Install docker CE in Amazon linux 2 
 Use the link below to install docker engine. Follow the steps 1 -6 in the link and restart the server. Aftre restart the docker services
 
 https://docs.aws.amazon.com/AmazonECS/latest/developerguide/docker-basics.html
 
 #Install docker-compose
 sudo curl -L https://github.com/docker/compose/releases/download/1.22.0/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose
 $ chmod +x /usr/local/bin/docker-compose
