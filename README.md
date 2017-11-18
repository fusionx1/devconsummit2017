# devconsummit2017

This example shows how to connect to Google Cloud SQL from an application running on Google Kubernetes Engine.

The mysql_wordpress_deployment.yaml manifest file that consists of two containers:

1. A web frontend container running WordPress.
2. A sidecar container for Cloud SQL Proxy container providing connectivity to Cloud SQL.
