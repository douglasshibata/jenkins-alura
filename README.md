# Learning Jenkins with Alura course

## Running Jenkins in docker
Pull Image
```bash
docker pull jenkins/jenkins:lts-jdk11
```
Run container
```bash
docker run --name jenkins -p 8080:8080 -p 50000:50000
```


## Running Jenkins using war file
```bash
java -jar jenkins.war --httpPort=8080
```
