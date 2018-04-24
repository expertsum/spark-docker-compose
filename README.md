# spark-docker

Use `docker-compose` to create a Spark standalone cluster on a single host. The following nodes are created:

- 1 master
- 1 worker
- 1 history server
- 1 jupyter notebook server

To start the cluster execute the following command:

`$ docker-compose up`

The different components can be accessed at the following URLs:

Component | URL
---|---
Master | http://localhost:8080/
Worker | http://localhost:8081/
History server | http://localhost:18080/
Jupyter notebook server | http://localhost:8888/

To shutdown the cluster execute the following command:

`$ docker-compose down`