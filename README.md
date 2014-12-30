scalatra-angularjs-examples
===========================

Implementation of AngularJS examples using Scalatra to serve RESTful Services.

to run project
==============

cd /root/project

$ sbt

sbt > compile

sbt > container:start

sbt > ~;copy-resources;aux-compile

localhost:8080

to run tests
============

cd /root/project

$ sbt

sbt > test:compile
sbt > test
