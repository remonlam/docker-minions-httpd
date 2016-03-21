Just a demo Docker file that will create a Docker images based on httpd and change the default index.html with a Minions index.html

docker build -t [build-name] .
docker run -d -p 8080:80 [build-name]
