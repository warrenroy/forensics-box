# Forensics-Box brought to you by Docker!

## Instructions:
1) Install docker, docker-compose, docker CLI
```
```
2) Git the repo warrenroy/forensics-box 
```
gh repo clone warrenroy/forensics-box
```
3) Add execute permissions to deploy.sh
```    
sudo chmod +x ./deploy.sh
```
4) Run deploy shell
```
./deploy.sh
```
5) Navigate to Kibana dashboard: [http://localhost:5601](http://localhost:5601)

### Link to article:
https://medium.com/@harisshafiq08/elk-stack-deployment-through-docker-compose-98ce40ff2fb6#:~:text=ELK%20stack%20deployment%20through%20docker-compose%20ELK%20Stack%20or,Kibana%29%20to%20manage%20and%20analyze%20the%20logs%20efficiently.

### Link to github repo:
https://github.com/Haris3243/docker-elkstack

First off all! as this example is based on Docker for Windows (Linux Mode), you have to swicth your deamon to linux container mode

Then open command line in the directory where you clonned this repository and just execute following command and it will up your elk stack and you can browse your kibana dashboard at http://localhost:5601

```
docker-compose up -d
```

Once ELK stack is up then you can deploy your app which logs you want to monitor through elk stack/kibana. For that puporse you have to route your container logs to tcp://localhost:8089 and logstash will capture those logs and then send to elasticsearch which will finally shows the logs in a pretty format on kibana.
