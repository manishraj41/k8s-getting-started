# docker builing an image from dockerfile
docker build -t fast-api-getting-started .
# docker running a container from image
docker run -d --name fast-api-getting-started-container -p 8000:80 fast-api-getting-started
docker images
docker container ls
docker rm -f 34cf2bee34ae
docker tag 97cd47ca4aec manishraj42/fast-api-getting-started:0.0.1
# pushing image to docker desktop registory
docker push manishraj42/fast-api-getting-started:0.0.1 


docker pull manishraj42/fast-api-getting-started:0.0.1

