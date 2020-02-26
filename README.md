# InfluxDB + Grafana set up - Microservices push metrics
Docker based microservices application to push metrics.

#### Pre-requisite
* Basic knowledge of docker & docker-compose
* Basic knowledge of maven project
* Basic idea of Influxdb (TSDB) and Grafana's role.

### Let's build and run both microservices and InfluxDB + grafana

```aidl
mvn clean install
docker-compose up -d --build
```
