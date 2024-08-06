FROM nginx
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY expense.conf /etc/nginx/nginx.conf
COPY index.html /usr/share/nginx/html/
COPY static /usr/share/nginx/html/
COPY asset-manifest.json /usr/share/nginx/html/