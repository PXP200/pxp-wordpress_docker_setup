This is meant to be a quick set up for local WordPress development. Not meant for deployment to a production environment.

If you already have Docker and Docker Compose installed.

With Docker installed and running, in Terminal:

````
git clone git@github.com:PXP200/pxp-wordpress_docker_setup.git
cd pxp-wordpress_docker_setup
````

Then:

````
docker-compose up -d
````

Then in your browser:
````
http://localhost:8000/
````

