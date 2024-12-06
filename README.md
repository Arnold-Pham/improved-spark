# Docker du Vendredi 6 Décembre

0 Connectez vous au docker hub
`docker login`

1 construire une image:
`docker build -t my-docker-image-webserver .`

2 Tester l'image localement
`docker run -d -p 9050:80 my-docker-image-webserver`

3 Tagger l'image pour Docker Hub 
`docker tag my-php-server <votre-identifiant>/my-docker-image-webserver:1.0`

4 Publier l'image sur Docker Hub
`docker push <votre-identifiant>/my-docker-image-webserver:1.0`

