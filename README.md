# Docker LEMP

This is Docker LEMP setup that I use for most of my PHP projects at this time.
Steps to use this setup:

* Clone this repository **https://github.com/Sparkqy/lemp-docker.git**
* Copy files from *lemp-docker* to *project* directory
* Edit docker-compose.yml:
	* Create unique names for every container (e.g *your-app-name_nginx* for nginx container)
	* Create unique name for network (e.g *your-app-name_app*)
	* Make sure you have your database credentials variables set in .env file
* Run *docker-compose* up in terminal
