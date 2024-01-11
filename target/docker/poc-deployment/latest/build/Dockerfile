FROM quay.io/jkube/jkube-java:0.0.20
ENV JAVA_OPTIONS=-Dquarkus.http.host=0.0.0.0 JAVA_APP_DIR=/deployments
LABEL org.label-schema.description="" org.label-schema.version=1.0.0-SNAPSHOT org.label-schema.schema-version=1.0 org.label-schema.build-date=2024-01-08 org.label-schema.name=poc-deployment
EXPOSE 8080 8778 9779
COPY /deployments /deployments/
WORKDIR /deployments
