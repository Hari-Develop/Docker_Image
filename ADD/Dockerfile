FROM almalinux
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://miro.medium.com/v2/resize:fit:1079/1*3ds-PdxGGMN-ZzJH95_lsA.png /usr/share/nginx/html/
ENV hari="DevOps Engineer"
LABEL software="Docker"
EXPOSE 8081/tcp
CMD [ "nginx","-g","daemon off;" ]

