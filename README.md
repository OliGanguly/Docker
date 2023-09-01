# Docker or Container
Used to Build App - A way to pack application with all necessary dependencies and configuration 
## Where do container live?
Container Lives in a Container Repository , Private Repository of a individual organization
or DockerHub (Public Repo)
## Before Docker - App Development
+ Before container developer had to install all the services on there machine and depending upon the OS , installation was diff
+ Many steps where something could go wrong
## After Cionatiner
+ No need to install in ur Os
+ Own isolated env
+ packed with all needed configuration when bundle up code
## Before Docker App Deployment
+ Development team produce artifact / Set of instractions how to install artifacts on the server , Like a jar file and send this to operations team
+ Operation team will handle setting up env
  ```bash
  Configuration on server needed
  Dependency version conflict
  Misunderstanding leads major issuee
  ```  
## After Docker App Deployment
+ Developer and operations working together as whole team to package application
+ So Container has its own env , so No env configuration needed on server
  ```bash
  Run a Docker Command That pulls container image that u stored in dockerHub / somewhere in repo
  Run it
  ```
## Container
Layers of Imagess / Linux Based

```bash
install docker.io
docker ps
docker pull postgres version
```

## Docker Image
actual package that is moveable
## Docker Container
when pull it in my local machine and start it / Running




