FROM jenkins/jenkins:lts

USER root

# Instalar Docker CLI y Docker Compose plugin dentro del contenedor Jenkins
# Instalar Docker CLI y Docker Compose
RUN apt-get update && \
    apt-get install -y docker.io docker-compose && \
    apt-get clean && rm -rf /var/lib/apt/lists/*

USER jenkins