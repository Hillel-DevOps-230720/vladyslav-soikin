1. Created Dockerfile.flask.
2. Run all the instractions to create mariadb container.
3. Run command "sudo docker build -t flask-app -f Dockerfile.flask .".
4. And finnaly start container based on this image "docker run -d --rm --name app -p 8000:8000 --link mariadb:db_server flask-app".

On docker hub you can find the image by this name: "14112236/flask-app".
