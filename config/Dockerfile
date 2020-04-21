FROM yobasystems/alpine-nginx

# Copy directory into container.
COPY ca /etc/nginx/ca
COPY ss /etc/nginx/ss
COPY nginx.conf /etc/nginx/nginx.conf

# Export container allow access ports.
EXPOSE 80
EXPOSE 443