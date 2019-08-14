FROM docker.io/ansible/centos7-ansible
LABEL image.description="This image has ansible and git on Centos"
USER root
WORKDIR /etc/ansible/hemant
RUN yum install git -y
#RUN mkdir /etc/ansible/hemant
RUN git clone https://github.com/hemantgirase/ansible.git /etc/ansible/hemant
RUN cp -R /etc/ansible/hemant/roles /etc/ansible/ && \
    cp /etc/ansible/hemant/hosts /etc/ansible
