FROM nginx
run rm -rf /usr/share/html/index.html
run rm -rf /etc/nginx/nginx.conf
run rm -rf /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY static /usr/share/nginx/html/


