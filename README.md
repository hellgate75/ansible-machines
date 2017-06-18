# ansible-machines

## Goals

Define automated docker containers playing Ansible playbooks and customizing dinamically, on the container start-up, the application eperience. They are used to define CI Pipelines.

## Content

At the moment we have following container images Ansible playbbok driven :
* [Centos 7](/centos-ansible)
* [Jenkins 2.32.3](/jenkins-ansible)
* [Nexus oss](/nexus-ansible)
* [SonarQube 6.2](/sonar-ansible)
* [PostgreSQL 9.6](/postgres-ansible)

Planning on : CouchDb, Convox and other docker images.

## Build

You can pull the images from : [DockerHub](https://hub.docker.com/r/hellgate75/), or
In the image folder you can run :
`docker build --tag hellgate75/<image>:<version>` 
or execute the `build.sh` script

## Run 
Any topic about execution is available in each image repositiory in [DockerHub](https://hub.docker.com/u/builditftorelli/)

## License

[MIT](/LICENSE)
