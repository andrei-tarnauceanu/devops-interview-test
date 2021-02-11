# Alfresco Content Services (ACS) Helm Chart

This chart deploys Postrges, ActiveMQ and the Alfresco repository.

The repository pod contains all the software/drivers required to connect to ActiveMQ & Postgres.

Once running the repository service is available via `NodePort`. Its web application is available at `http://NodeIp:NodePort/alfresco`.
