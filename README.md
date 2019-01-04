# hetzner-docker-jenkins-artifactory

```
docker run -d --rm -u root -v /var/run/docker.sock:/var/run/docker.sock -v /Users/stefan/tmp/jenkins-data:/var/jenkins_home -e VIRTUAL_HOST=jenkins.localhost -e VIRTUAL_PORT=8080 jenkinsci/blueocean
```

```
docker run -d --rm -p 80:80 -p 443:443 -v /var/run/docker.sock:/tmp/docker.sock:ro  jwilder/nginx-proxy
```
