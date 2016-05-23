FROM nginx:1.9.15-alpine

COPY nginx.conf /etc/nginx/nginx.conf

Expose 41234/udp

CMD ["nginx", "-g", "daemon off;"]
