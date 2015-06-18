# vagrant-docker
Test project to deploy docker containers with vagrant
## Requirements for windows
- Install VirtualBox
- Install Boot2Docker (optionally, if you want to test docker containers out of vagrant)
- Install Vagrant
- Install rsync and ssh package with cygwin

##Usage

###docker-vertex
Docker-vertex is running the web server vertx in a container without database
Run the `vagrant up` command in the *docker-vertex* folder using cygwin (or else if rsync and ssh are available). 

Then you can acces to a minimalist http server with the address : `http://localhost:8181`

##docker-node
Docker-node is running a minimalist nodejs web server without database
Run the `vagrant up` command in the *docker-node* folder using cygwin (or else if rsync and ssh are available). 

Then you can acces to a minimalist http server with the address : `http://localhost:8282`
