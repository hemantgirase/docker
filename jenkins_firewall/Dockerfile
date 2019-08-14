FROM jenkins
RUN yum install firewall-cmd -y
RUN firewall-cmd --zone=public --permanent --add-port=8080/tcp
RUN firewall-cmd --reload
