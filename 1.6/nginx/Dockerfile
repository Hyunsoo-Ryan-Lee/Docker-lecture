FROM nginx:alpine
RUN echo "hello world" > /home/hello.txt
ENV CODEIT Sprint
EXPOSE 5050
WORKDIR /usr/share/nginx/html
COPY index.html /usr/share/nginx/html/index.html