#build docker image
docker build -t devops-code-challenge

#run docker container
docker run -it -p  3080:3080 --name devops-challenge devops-code-challenge