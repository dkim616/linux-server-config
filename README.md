# Linux Server Configuration Project

IP Address: 54.200.28.115
SSH port: 2200

Web App URL: http://54.200.28.115/

Installed software:
- finger
- postgres (sqlite3 was used for the web app)
- flask
- oauth2client
- requests
- httplib2
- pip
- sqlalchemy
- apache2
- libapache2-mod-wsgi

Configuration Changes Made:
- SSH port change from 22/tcp to 2200/tcp
- Port enabled for 80/tcp and 123/tcp and blocked all other ports by default
- Created new user grader with sudo permissions
- SSH keygen generated for grader
- Apache configuration changes to /etc/apache2/sites-enabled/000-default.conf
