# dind-nodejs-jenkins-slave
Docker-in-Docker Jenkins Slave to build docker image for nodejs project. This image is based on [tehranian/dind-jenkins-slave](https://github.com/tehranian/dind-jenkins-slave) image. It contains :

- docker
- nodejs 6.x
- g++
- make
- python
- Java JRE 7 (for jenkins)

You can log using `jenkins` user (password is `jenkins`) with SSH.
