FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/KosaraSurya/roboshop-infra-dev/refs/heads/main/60-catalogue/main.tf /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
#ADD sample.tar /tmp
CMD ["nginx","-g","daemon off;"]