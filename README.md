# Jenkins docker

*In this Dockerfile, i add the library to build docker image.*

Launch the jenkins docker :
```
docker run -d -p 49001:8080 -t jenkins/jenkins
```
Add a volume :
```
add -v $PWD/jenkins:/var/jenkins_home
```
To use completely java build jenkins, we need to add JDK 8 and Maven 3.5.0
