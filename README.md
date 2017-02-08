This is a simple demo of running tests for rust using a docker image from docker hub. 

Unit test code came from http://rustbyexample.com/meta/test.html

Notes on deploying:

* May need to install TaskCluster integration https://github.com/integration/taskcluster
* How do we see pushes for "main line" commits

== Steps to set up a new repo

* Create a .taskcluser.yml (https://tools.taskcluster.net/quickstart/)
* Select an appropriate docker image & update

