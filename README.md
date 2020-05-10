# elasticsearch-kibana-docker-compose
docker-compose file for setting up a local elasticsearch-kibana environment using docker-compose


### install docker
```sudo yum install docker```

```sudo service docker start```

```sudo usermod -a -G docker ec2-user```


### install docker compose
```sudo curl -L "https://github.com/docker/compose/releases/download/1.23.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose```

```sudo chmod +x /usr/local/bin/docker-compose```

```sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose```

### Run the docker containers
```docker-compose up -d```

### View the Kibana Dashboard

Kibana dashboard will be accesible in your favorite browser at [localhost](http:://localhost:5601)
