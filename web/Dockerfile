FROM nginx:1.10

ADD ./vhost.conf /etc/nginx/conf.d/default.conf
ADD ./elastic.conf /etc/security/limits.d

RUN echo "DefaultLimitNOFILE=65536" >> /etc/systemd/user.conf
RUN echo "DefaultLimitNOFILE=65536" >> /etc/systemd/system.conf
RUN echo "DefaultLimitNOFILE=65536" >> /etc/security/limits.conf

WORKDIR /var/www
