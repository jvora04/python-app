# python-app

#Docker Install command 
sudo apt-get remove docker docker-engine docker.io containerd runc // remove older version of docker
curl -fsSL https://get.docker.com -o get-docker.sh // download the copy of script
DRY_RUN=1 sh ./get-docker.sh
docker
sudo sh get-docker.sh // install docker by running this file

sudo docker version
