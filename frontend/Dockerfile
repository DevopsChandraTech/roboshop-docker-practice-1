FROM nginx:1.24
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /usr/share/nginx.conf
RUN rm -rf /usr/share/conf.d/default.conf
COPY static /usr/share/nginx/html
COPY nginx.conf /usr/share/nginx.conf
