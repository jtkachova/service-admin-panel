# service-admin-panel
admin panel on flask with login page, which provides restart critical application services on remote servers.

###Requirments

-Python

-pip

-Flask==0.10.1

-Flask-DebugToolbar==0.9.2

-python-ldap==2.4.17

### Install

pip -r requirments.txt

###Configuration

in app.py file function login specify ldap_server and user_dn variables.

In *.php files  specify ip, username, password, path to key. Php files allow restart services remotely, in our case nginx and uwsgi.You can change services, which should be restart, in these files.







