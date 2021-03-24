---
services: app-service\web,app-service
platforms: python
author: cephalin
---

# Django and PostgreSQL sample for Azure App Service

This samples is a simple Django app that connects to a PostgreSQL database. Please refer to the corresponding tutorials to get started with this sample repo.

When deployed to Azure App Service, the database connection information is specified via environment variables `ResourceConnector_DB_TargetServiceEndpoint`, `ResourceConnector_DB_Key`, `ResourceConnector_DB_Name`, and `ResourceConnector_DB_SubResourceName`. This app always uses the default PostgreSQL port. See the tutorials for more information.
