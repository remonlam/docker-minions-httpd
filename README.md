Just a demo Dockerfile that will create a Docker image based on httpd and change the default index.html with a Minions index.html

docker build -t [build-name] . <br>
docker run -d -p 8080:80 [build-name]
