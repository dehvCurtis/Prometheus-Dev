## Running the Code

Run the following command to start up the containers:

```
$ docker-compose up -d
```

Access the dashboards with the following URLs:

    Alertmanager: http://localhost:9093
    Grafana: http://localhost:3000 (user/password: admin)
    Prometheus: http://localhost:9090
    Sample Node.js Application: http://localhost:4000

## Run the following command to stop all running containers from this project:

```
$ docker-compose rm -fs
```
