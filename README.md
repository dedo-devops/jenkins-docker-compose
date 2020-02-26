# jenkins-docker-compose                                                                                                                        

run jenkins in docker container

git clone https://github.com/dedo-devops/jenkins-docker-compose.git

docker-compose up -d 

docker exec jenkins-docker cat /var/jenkins_home/secrets/initialAdminPassword
