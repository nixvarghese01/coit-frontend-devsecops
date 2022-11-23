FROM nginx:1.23.2-alpine
COPY build /usr/share/nginx/html
RUN adduser -D dev && chown dev /usr/app/build && chmod 400 /usr/app/build && mkdir /usr/app/uploads && chown -R dev /usr/app/uploads && chmod 700 /usr/app/uploads
