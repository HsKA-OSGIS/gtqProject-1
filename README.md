
# gtQ

#Project repository for Team getThereQuick

General Usage notes for gtQ Open Source Project January 2015 - HsKA

#About Project

gtQ Open Source GIS project is a project focused on utilizing open source resources to create a project  focused in South Africa about the general usage of roads for locals and also tourist. The project also has additional functionalities such as what do to and place to visit.
Software Used
Applications

1.	QGIS
	
  •	Data authentication (visualization and editing).

  •	PostgreSQL (PostGIS – pgRouting extension).

2.	Linux terminal

	  •	pgAdmin 3

3.	pgRouting
	
  • SQL Queries.

  • http://docs.pgrouting.org/dev/doc/src/tutorial/index.html

4.	Geoserver
	
  •	Publishing our Map.

5.	Open Layers 3
	
  •	Open Layers 3 API Library

  •	http://openlayers.org/en/v3.1.1/doc/tutorials/

#Instructions to run the program

  •	Firstly the user should copy all files to their local drive.

  •	The gtQ web map supports Linux Software as well as Windows software provided, the user should download OSM data for   their place of interest, should you want to have results looking similar to what we have in the main project then     Johannesburg OSM roads data would be relevant.

#Storage

  All files should be stored in one folder to avoid omitting necessary links to other files or parts of the project.


#How to load ‘gtQ’ client application in Apache httpd web server

* All files are simple to run and easy to understand
* The application can been tested with Apache httpd 2.4.7
* Clone this repository into your local folder (say, 'gtq')
* Copy the ‘gtqProject-1’ folder in /var/www/html folder of OSGeo-Live
* The home.html within 'gtq' will be visible in the browser at location http://localhost:80/gtq/       (localhost/gtqproject as shortcut)
* If you want to create more advanced or virtual locations, then create a new configuration in /etc/apache2/conf-available folder


#LICENSE

Please refer to the License file.

#Authors

Maclean Commey - macgeomatics@gmail.com

Monale Langa   - sepharihla@gmail.com
