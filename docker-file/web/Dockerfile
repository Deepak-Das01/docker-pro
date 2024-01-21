FROM nginx
LABEL authors="deepakdas"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginxmain.conf /etc/nginx/conf.d/nginxmain.conf

ENTRYPOINT ["top", "-b"]