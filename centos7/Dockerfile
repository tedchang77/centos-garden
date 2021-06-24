FROM centos:7
RUN yum update -y
RUN yum install -y git rsync curl
RUN curl -sL https://get.garden.io/install.sh | bash
RUN echo 'export PATH=$PATH:$HOME/.garden/bin' >> ~/.bashrc