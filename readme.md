# build docker

docker build -t hello-docker .
-> -t is a tag to identify

# list the images of docker

docker image ls
-> docker add the tag:latest by default
-> we use this tag for versioning our images
-> so each image can contain a different version of application
-> each imgae has unique identifier 
-> because of linux:alphine we have disk usage 249mb

# so

we can run this image on any computer running docker

# running docker

docker run hello-docker

# pull the image from docker

-> docker pull codewithmosh/hello-docker
-> docker image ls -- the repository should be codewithmosh/hello-docker