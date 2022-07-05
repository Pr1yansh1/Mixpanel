# CoffeeSpace's Nginx Proxy for Mixpanel
CoffeeSpace's nginx config that serves as a proxy to Mixpanel's Ingestion API and JavaScript library endpoints. 
Some resources: 
[Mixpanel- Collection Via Proxy](https://developer.mixpanel.com/docs/self-hosted-tracking).  \ 
[GitHub Sample Nginx Proxy](https://github.com/mixpanel/tracking-proxy).  \ 
[Mixpanel Infrastructure doc](https://docs.google.com/document/d/1DIVXKxiydzp4QxL3D0d0M1sMy6AL47amYa3wOr25c6A/edit). \   


## Installation

There are a few ways you can use this repo to deploy a server that can be use to proxy Mixpanel API requests: one-click deploy to cloud, build a docker image, or copy and paste the nginx settings to your own nginx config file.

### Option 1: One-click Deploy
   - [![Deploy to Digital Ocean](https://www.deploytodo.com/do-btn-blue.svg)](https://cloud.digitalocean.com/apps/new?repo=https://github.com/Pr1yansh1/Mixpanel/tree/main)
   
### Option 2: Docker Image
   Assuming you have Docker installed on your system, for production, deploy this docker image to whatever servers contain the production services. 

### Option 3: Add locations to your existing Nginx config
   If you already have servers running nginx, you can copy and paste the locations from the [nginx.conf](https://github.com/Counselab-Inc/Mixpanel-Proxy/blob/master/nginx.conf) file in this repo and adjust the locations to match your preference.
