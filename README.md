# static-website-docker-image
Build image: docker build -t webserver .
Run container: docker run -it --rm -d -p 8080:80 --name web webserver