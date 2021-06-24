# centos-garden
## centos 7
docker build . -t centosa7-garden
docker tag centos7-garden tedchang77/centos7-garden
docker push tedchang77/centos7-garden:latest

### sqlite3 version
docker run -it tedchang77/centos7-garden bash
[root@0912a23906e6 /]# /usr/bin/sqlite3
SQLite version 3.7.17 2013-05-20 00:56:22 



## centos 8
docker build . -t centos8-garden
docker tag centos8-garden tedchang77/centos8-garden
docker push tedchang77/centos7-garden:latest
docker run -it tedchang77/centos8-garden bash

### sqlite not installed
[root@958220d5abba /]# yum install sqlite
Last metadata expiration check: 0:15:57 ago on Thu 24 Jun 2021 04:09:24 AM UTC.
Dependencies resolved.
==================================================================== Package      Architecture Version               Repository    Size 
====================================================================Installing:
 sqlite       x86_64       3.26.0-13.el8         baseos       667 k 

Transaction Summary
====================================================================Install  1 Package

Total download size: 667 k
Installed size: 1.3 M
Is this ok [y/N]:
