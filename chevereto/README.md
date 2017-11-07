# Chevereto docker
***
## How to run
```
git clone https://github.com/c-ardinal/my-app-compose.git
cd my-app-compose/chevereto
docker-compose up -d
```
***
## Customize upload size
1. Open "php.ini".
2. Change "upload_max_filesize" and "post_max_size".
3. Copy "php.ini" into BUILD IMAGE, or execute commands.
```
docker build .
docker tag {BUILD_IMAGE} cardina1/chevereto-docker
docker-compose up -d
```
***
