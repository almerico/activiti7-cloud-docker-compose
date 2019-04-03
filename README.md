# activiti7-cloud-docker-compose

##Prerequisite:
Change DOCKER_IP to your ip in .env

##Start options
For starting whole system
```
make all
```
For starting all services without modeller 
```
make application 
```

For starting modeler and keycloak
```
make modeler
```

To see logs 
```
make logs 
```

Other available actions
```
make help
```

##Modeller 
To access modeler please use url 
http://<<yourgateway>>/activiti-cloud-modeling
For example  
http://192.168.1.9.nip.io/activiti-cloud-modeling
You will be redirected to keycloak where you have to use credentials *modeler/password*  
