# udacity
General Udacity project items.

## Host Information
```
IP: 52.3.229.8
SSH PORTS ALLOWED: 2200 and 22
```

`NOTE`: On the first review I was 'dinged' for continuing to
allow traffic to port 22. This was done because if you disable
traffic to 22/tcp then the built-in Lightsail console will 
cease to function. I purposely allowed traffic on BOTH TCP 
ports 22 and 2200. Please take that into account when 
reviewing other assignments.


## Third party tooling and references
As requested I'm putting information in here on thirdy-party 
tooling and/or references. Outside of the docs provided 
through https://help.ubuntu.com I didn't use any outside 
resources or tooling to configure the system. I was already
familiar with GNU/Linux systems and AWS when starting this
assignment.


## Application Information
The application leverages Auth0 based authentication, Python, 
the Python Flask micro-framework, Pip, Gulp, PostgreSQL, 
SQLAlchemy-Migrate, Apache2, uWSGI, the Apache2 uWSGI proxy 
module and a variety of other items.

The application may be accessed at http://52.3.229.8/ .

I've confirmed the deployment by creating a `Test` category.

