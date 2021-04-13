# Forensics-Box brought to you by Docker and Elastic!

## Instructions:
1) Install docker, docker-compose, docker CLI (this step will vary depending on if running on Windows, Linux, Mac)
```
https://desktop.docker.com/win/stable/Docker%20Desktop%20Installer.exe
gh repo clone docker/compose
```
2) Git the repo warrenroy/forensics-box 
```
$ gh repo clone warrenroy/forensics-box
```
3) Add execute permissions to deploy.sh
```    
$ sudo chmod +x ./deploy.sh
```
4) Run deploy shell
```
$ ./deploy.sh
```
5) After the application starts, navigate to below links in your web browser:
* Elasticsearch: [`http://localhost:9200`](http://localhost:9200)
* Logstash: [`http://localhost:9600`](http://localhost:9600)
* Kibana: [`http://localhost:5601`](http://localhost:5601)

### Official Docker ELK repo:
https://github.com/docker/awesome-compose/tree/master/elasticsearch-logstash-kibana

### Link to other Docker ELK repo:
https://github.com/deviantony/docker-elk
https://github.com/sherifabdlnaby/elastdocker

### Future development? (network traffic packet capturer)(linux audit platform):
https://hub.docker.com/_/packetbeat
https://hub.docker.com/_/auditbeat

### Link to article:
https://medium.com/@harisshafiq08/elk-stack-deployment-through-docker-compose-98ce40ff2fb6#:~:text=ELK%20stack%20deployment%20through%20docker-compose%20ELK%20Stack%20or,Kibana%29%20to%20manage%20and%20analyze%20the%20logs%20efficiently.

### Link to github repo:
https://github.com/Haris3243/docker-elkstack
