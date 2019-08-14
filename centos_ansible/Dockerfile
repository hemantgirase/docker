FROM docker.io/ansible/centos7-ansible
RUN yum install git -y
RUN mkdir /etc/ansible/hemant
RUN git clone https://github.com/hemantgirase/ansible.git /etc/ansible/hemant
RUN cp -R /etc/ansible/hemant/roles /etc/ansible/ && \
    cp /etc/ansible/hemant/hosts /etc/ansible
