docker pull jenkins/jenkins

docker run -d -p 49001:8080 -t jenkins/jenkins

add -v $PWD/jenkins:/var/jenkins_home if we want to have a volume

Need to add JDK 8 and Maven 3.5.0