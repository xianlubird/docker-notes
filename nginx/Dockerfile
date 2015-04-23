FROM nginx

COPY nginx.conf /etc/nginx/nginx.conf
COPY registry.conf /etc/nginx/conf.d/registry.conf
COPY docker-registry.conf /etc/nginx/conf.d/docker-registry.conf
COPY docker-registry-htpasswd /etc/nginx/docker-registry-htpasswd

EXPOSE 5000 
