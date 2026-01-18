FROM nginx:latest 
RUN apt update -y && rm -rf /usr/share/nginx/html/*
COPY app.* /usr/share/nginx/html/
EXPOSE 9090:80



