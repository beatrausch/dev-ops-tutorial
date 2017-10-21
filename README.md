# DevOps Tutorial


## Jenkins
Jenkins is an open source automation server written in Java. Jenkins helps to automate the non-human part of software development process, with continuous integration and facilitating technical aspects of continuous delivery. 

To run Jenkins for testing can simply achived by using docker:
```shell
docker run --name myjenkins -p 8080:8080 -p 50000:50000 -v /var/jenkins_home jenkins
```
