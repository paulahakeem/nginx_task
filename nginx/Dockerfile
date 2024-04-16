FROM nginx:latest
RUN apt-get update && apt-get install -y procps
RUN apt-get install --no-install-recommends -y apache2-utils
RUN mkdir -p /home/download
RUN mkdir -p /etc/pwd