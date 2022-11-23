FROM nginx:1.23.2-alpine
COPY build /usr/share/nginx/html
RUN adduser -D dev && chown dev /usr/share/nginx/html && chmod 400 /usr/share/nginx/html && mkdir /usr/app/uploads && chown -R dev /usr/app/uploads && chmod 700 /usr/app/uploads
