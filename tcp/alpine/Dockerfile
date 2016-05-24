FROM nginx:1.9.15-alpine

COPY default.conf /etc/nginx/conf.d/default.conf

COPY STAR_aerisdev_com.pem /etc/ssl
COPY star_aerisdev_keystore.pem /etc/ssl

Expose 8443/tcp

CMD ["nginx", "-g", "daemon off;"]
