FROM nginx:latest

RUN cp -r /etc/nginx /etc/nginx.original; \
rm -rf /etc/nginx/nginx.conf /etc/nginx/conf.d /etc/nginx/snippets /etc/sites-enabled \
/etc/nginx/templates /var/log/nginx/access.log /var/log/nginx/error.log; \
ln -s /workspace/nginx.conf /etc/nginx/nginx.conf; \
ln -s /workspace/conf.d /etc/nginx/conf.d
