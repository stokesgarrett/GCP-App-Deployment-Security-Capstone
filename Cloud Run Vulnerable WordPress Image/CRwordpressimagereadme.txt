This folder contains the specific wordpress image we deployed to Google Cloud Run. Unfortunately, we are not allowed to supply the image directly into this directory, as docker pulls
do not necessarily save the image on the host machine. However, the exact command we used to make the image accessible on our Docker Desktop application is as follows -
docker pull wordpress:beta-6.4-RC2-apache
