FROM almalinux:9
RUN  yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
ADD  https://github.com/Sharath3116/shellscript/blob/main/roboshop/MongoDB.sh /tmp/
CMD ["nginx", "-g","daemon off;"]
