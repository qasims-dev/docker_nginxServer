command to run in local directory first

 docker container run -d -p 8080:80 -v $(pwd):/usr/share/nginx/html --name nginx-website nginx

