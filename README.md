create amazon linux machine
follow below steps to install docker
update the packages.
	sudo yum update -y
 Install the docker.
	sudo yum install -y docker
sudo service docker start
sudo docker --version


if we want check docker images in our machine

docker images

if we want to run docker images

docker run -it imagename

if we run above command, it will creates container

if we want to check what are containers running in our machine

docker ps

if you want to pull anything 

docker pull

if you want to push anything to docker server

we need to tag that image then push that docker image

docker tag imageid dockerid/image:version

ex;docker tag cd14cecfdb3a venkat0007/jenkins:1

and push it like below

docker push

