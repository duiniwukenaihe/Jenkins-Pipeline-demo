# Jenkins-Pipeline-demo

修改 Jenkinsfile:
```
SONAR_SERVER 地址修改为你的 sonar 地址
DOCKER_REGISTRY 地址修改为你的 docker registry 地址
DEPLOY_HOST 地址修改为你的 docker daemon 地址
```

pipeline 截图：

![](https://raw.githubusercontent.com/opspy/Jenkins-Pipeline-demo/master/img/pipeline.jpg)

访问地址为
```
http://DEPLOY_HOST的IP:9090/greeting
```
