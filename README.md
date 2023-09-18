# DemoApp

Starting point for development

ng new demo-app

Added Dockerfile and ./config/nginx.conf
Uses nginxinc/nginx-unprivileged container image

docker build -t taylok/demo-angular-nginx:v0.1.0 .
docker push

Added demo-deplpoyment.yaml

oc apply -f demo-deployment.yaml



