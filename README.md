This is meant to be a quick set up for local WordPress development. Not meant for deployment to a production environment.

If you already have Docker and Docker Compose installed.

With Docker installed and running, in Terminal:

````
git clone git@github.com:PXP200/pxp-wordpress_docker_setup.git
````

Change the name of the directory
````
mv pxp-wordpress_docker_setup [your project name]
cd [your project name]
````
Remove git from root
````
rm -rf .git
````

Now you can either start a new theme in wp-content/themes or clone a theme into wp-content/themes.


Then:

````
docker-compose up
````

Then in your browser:
````
http://localhost:8000/
````

