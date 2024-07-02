FROM nginx:alpine

COPY nginx.conf /etc/nginx/conf.d/default.conf

# Copy SSL certificates
COPY /etc/letsencrypt /etc/letsencrypt

EXPOSE 80
EXPOSE 443