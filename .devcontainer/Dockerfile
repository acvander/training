FROM eclipse-temurin:21-jammy

# download nextflow
RUN curl -s https://get.nextflow.io | bash

# make nextflow executable and move it to /usr/local/bin
RUN chmod +x nextflow \
    && mv nextflow /usr/local/bin/nextflow

# set java home in bashrc
RUN echo "export JAVA_HOME=/opt/java/openjdk" >> /root/.bashrc
