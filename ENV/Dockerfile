# FROM almalinux
# RUN yum install nginx:1.27-bookworm-perl -y
# LABEL Hari="DevOps"
# ENV Docker="software"
# CMD ["nginx","-g","daemon;"]

FROM almalinux:latest

# Install Nginx with the specified version
RUN yum install nginx:1.27-bookworm-perl -y

# Label for informational purposes
LABEL maintainer="Hari (DevOps)"

# Environment variable (optional)
ENV Docker="software"

# Start Nginx in daemon mode (optional: adjust daemon off)
CMD ["nginx", "-g", "daemon off"]
