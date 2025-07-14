# demo-java-test
this is a poc of a java springboot application build on gradle and deployed in k8s with observability in Prometheus, fluentd and Grafana.
## Directory Structure

springboot-k8s-observability/
├── Dockerfile
├── build.gradle
├── settings.gradle
├── k8s/
│   ├── deployment.yaml
│   ├── service.yaml
│   ├── prometheus-config.yaml
│   ├── grafana-datasource.yaml
│   └── filebeat.yaml
├── src/
│   └── main/
│       ├── java/com/example/demo/
│       │   ├── DemoApplication.java
│       │   └── controller/HelloController.java
│       └── resources/
│           └── application.yml