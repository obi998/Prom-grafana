#Slight revamp of the below for Obi.

IMPORTANT NOTE: 
This requires following /etc/host entries to work.

127.0.0.1       prombox  

127.0.0.1       grafana  

127.0.0.1       exporter  


# Quickstart for Prometheus

Get up and running with Prometheus and node-exporter with a `docker-compose.yml` file in less than 5 minutes.

### Running the example

```
$ git clone https://github.com/alexellis/quickstart-prometheus
$ cd quickstart-prometheus
$ docker-compose up -d
```
Open a browser and point at http://localhost:9090/

### See also:

* [Node Exporter](https://github.com/prometheus/node_exporter)

* [Querying Prometheus](https://prometheus.io/docs/querying/basics/)

