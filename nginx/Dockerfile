FROM nginx:alpine

# copy Nginx config files
COPY default.conf /etc/nginx/conf.d/
COPY nginx.conf /etc/nginx/

# set file permissions for nginx user
RUN chown -R nginx:nginx /var/cache/nginx /etc/nginx/

# switch to non-root user
USER nginx

CMD ["nginx", "-g", "daemon off;"]