# Monitoring

4 times Intel(R) Xeon(R) CPU E7-4830 v4 @ 2.00GHz

64GB of ram

2 tb HDD disk space

2 x 10Gbit/s nics

The server is used for SSL offloading and proxies around 25000 requests per second.



###  Installation needed :
Prometheus server : https://prometheus.io/

Prometheus node exporter : https://github.com/prometheus/node_exporter

SSL expoter : https://github.com/ribbybibby/ssl_exporter

Grafana server : https://grafana.com/



### Metrics 

CPU : How % of consuming 

Memory : Used and Free

Disk : Disk throughput , Disk usage

Network : Package in , Package out , Network throughput

Process : How many process run

Requests per sec : monitoring how many load of this server

SSL : When SSL expired 
