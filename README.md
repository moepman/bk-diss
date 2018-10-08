# Binary Kitchen: Directory Self-Service

## Overview

TBA

## Requirements

* passlib >= 1.7.0
* flask >= 0.12.1
* flask-wtf >= 0.14.2
* ldap >= 2.4.25
* redis >= 2.10.5

## uWSGI

To use dss with uWSGI create a file called uwsgi.ini from the provided example and change the socket and optinally the chroot setting. You can use `/usr/bin/uwsgi --ini /path/to/dss/uwsgi.ini` to start your instance.

## Misc

Source code is under MIT license, powered by Flask and Bootstrap.
