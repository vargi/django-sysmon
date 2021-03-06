django-sysmon
=============

Simple System Monitoring in Django Admin Panel

Features
=============

- CPU Usage
- Memory Usage
- Disk Usage (with partitions)
- Network Usage
- TOP 10 memory used processes
- Viewing only superuser
- It currently supports Linux, Windows, OSX and FreeBSD (psutil supported)

Requirements
=============
- psutil (https://pypi.python.org/pypi/psutil)

Screenshots
=============
![Screenshot](https://raw.github.com/hakanzy/django-sysmon/master/docs/screen.png)


Installation
=============

 - Put sysmon folder in your django applications folder, and add sysmon into your INSTALLED_APPS
 - That's all.
