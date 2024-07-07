FROM almalinux
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
ENV hari="Hari(DEVOPS ENgineer)"
LABEL software="Docker"
EXPOSE 8081/tcp
CMD [ "nginx","-g","daemon off;" ]