FROM registry.redhat.io/amq7/amq-streams-kafka-28-rhel8:1.8.4
USER root:root
COPY ./my-plugins/ /opt/kafka/plugins/
COPY ./jdbc/ /opt/kafka/libs/
USER 1001
