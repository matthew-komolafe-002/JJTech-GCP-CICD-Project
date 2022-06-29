## JJTech GCP CICD Project Runbook

### SonarQube Credentials (Will be using in Maven)
```
Token: jjtech-cicd-java-project: c72746fbaf7d40701e3b14c45014ac1a13711688
```
```
mvn sonar:sonar \
  -Dsonar.host.url=http://34.125.120.45:9000 \
  -Dsonar.login=c72746fbaf7d40701e3b14c45014ac1a13711688
```
```
username: admin
password: admin
```

### Nexus Credentials
```
username: admin
password: admin
ip address: 34.125.127.201:8081
```


### Maven Credentials
```
username: 
password: 
ip address: 34.125.41.221
```


### Ansible Credentials
```

```


### Jenkins Credentials
```
username: admin
password: admin
ip address: 34.125.41.221:8080
```


### Github Credentials
```
webhook: http://34.125.41.221:8080/github-webhook/
```