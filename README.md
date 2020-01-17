# Jenkins project
To run a fully functional jenkins server just ran:
```bash
    docker run -d -p 8080:8080 -p 50000:50000 --name jenkins -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts
```
