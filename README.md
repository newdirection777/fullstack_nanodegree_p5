This web app provides a simple database for the sport of boxing.
It allows you to add, edit, and delete your favorite fighters.

IP Address: 52.27.111.124
URL: ec2-52-27-111-124.us-west-2.compute.amazonaws.com

Summary of installed software:
-Apache web server and mod_wsgi module
-Git
-Flask
-python-pip
-virtualenv
-httplib2
-oauth2client
-sqlalchemy
-psycopg2
-PostgreSQL

Summary of configuration changes made:
-created new user grader with sudo privileges.
-did a software update.
-set timezone to UTC.
-changed ssh port from 22 to 2200.
-allow ssh key login only.
-disabled remote login for root.
-configured firewall to only allow connections for: ssh, http, ntp.
-copied application files from Github using git.
-created new user named catalog for database access.
-configured postgres database named catalog to serve the web app data.
-configured catalog database to be writable by user 'catalog' only.
-configured web server to serve catalog application as wsgi app.
-set up Flask to serve the catalog application.
-set up SQLAlchemy to handle database functions.
-configured oauth logins for Google and Facebook accounts.


Third party resources used to complete this project:
-Ubuntu documentation
-Digital Ocean server setup documentation
-PostgreSQL documentation
-Flask documentation
-SQLAlchemy documentation
-Stackoverflow
-Udacity forums


To use this app:
-Point your browser to the URL shown above. This will bring up the home page.

-Click the 'login' link in the upper right corner, and log in using your
Google or Facebook account.  For best results, use Chrome.  Facebook
login may not work on Firefox because of the default security settings
on Firefox.

If you MUST use Firefox, set 'Allow Tracking' to True in your settings.

-Once you are logged in, you can add, edit, delete fighters.  Enjoy!