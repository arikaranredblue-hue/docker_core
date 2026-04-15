FROM nginx:1.25-alpine

RUN addgroup -S appgroup && adduser -S appuser -G appgroup && \
    rm -rf /usr/share/nginx/html/*

COPY . /usr/share/nginx/html/

COPY nginx.conf /etc/nginx/nginx.conf

RUN chown -R appuser:appgroup /usr/share/nginx/html/ \
    /var/cache/nginx \
    /var/log/nginx 

EXPOSE 80

CMD [ "nginx" , "-g" , "daemon off;"]

