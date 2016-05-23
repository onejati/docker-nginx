FROM nginx:1.9.15-alpine

COPY nginx.conf /etc/nginx/nginx.conf

Expose 443/tcp

CMD ["nginx", "-g", "daemon off;"]
