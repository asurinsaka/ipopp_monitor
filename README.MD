To build the image, use the command:
docker build -t <image_name> .
To run the docker, use the following command: 
docker run --rm -p 3306:3306 --name <container_name> -e MYSQL_ROOT_PASSWORD=1234 -e MYSQL_DATABASE=DSM <image_name>
