# Docker du Vendredi 6 Décembre

0 Connectez vous au docker hub

`docker login`

1 construire une image:

`docker build -t image-spark .`

2 Tester l'image localement

`docker run -d -p 9050:80 image-spark`

3 Tagger l'image pour Docker Hub 

`docker tag image-spark arnoldp/docker-apache-g2r:1.0`

4 Publier l'image sur Docker Hub

`docker push arnoldp/docker-apache-g2r:1.0`

