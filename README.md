IP address: http://204.236.206.70/

URL: http://http://204.236.206.70//catalog/

Software Installed: Flask, httplib2, Jinja2, oauth2client, psycop2, requests, rsa, six, SQLAlchemy, Werkzeug, pyasn1, pyasn1-modules

Configurations made:
Created new user named grader and given ssh-key gen
Changed local timezone to UTC
Allowed UFW to only allow incoming connections for SSH, HTTP, and NTP
Changed SSH port from 22 to 2200
Updated all currently installed packages
Installed and configured Apache2 for a mod_wsgi app
Cloned a modified version of Item-Catalog for app
Made it so can't log into root

Resources used:
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
https://www.digitalocean.com/community/tutorials/how-to-create-remove-manage-tables-in-postgresql-on-a-cloud-server
http://newcoder.io/scrape/part-3/