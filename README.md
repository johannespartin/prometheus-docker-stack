# Prometheus + Grafana 

Prometheus and Grafana stack implementation with Docker. Access to both apps is authorized through an Nginx+OAuth2-Proxy implementation.
Authentication provider in this case is Azure AD.

## Components

- NGINX
- OAUTH2 Proxy
- Prometheus
- Grafana

## Setup

Environment variables:
- OAUTH_CLIENT_ID
- OAUTH_CLIENT_SECRET
- OAUTH_TENANT_ID
