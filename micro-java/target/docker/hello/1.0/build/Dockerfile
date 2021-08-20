FROM fabric8/s2i-java:2.3
ENV AB_PROMETHEUS_OFF=true JAVA_APP_DIR=/deployments
LABEL org.label-schema.description="Hello microservice using Thorntail" org.label-schema.version=1.0 org.label-schema.schema-version=1.0 org.label-schema.build-date=2021-08-19T21:02:49.653 org.label-schema.name="Red Hat Training Hello Java app" org.label-schema.vcs-ref=2c8dcd8dd9a8ec2c95afa13d8848d36f64d9ed3d org.label-schema.vcs-url=https://github.com/SirVL/DO288-apps.git
EXPOSE 8080 8778 9779
COPY maven /deployments/
