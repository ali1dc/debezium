FROM debezium/connect:0.9.5.Final

RUN curl http://central.maven.org/maven2/io/prometheus/jmx/jmx_prometheus_javaagent/0.3.1/jmx_prometheus_javaagent-0.3.1.jar > /kafka/jmx_prometheus_javaagent.jar

COPY prometheus-config.yml /kafka/config.yml
