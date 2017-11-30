FROM openshift/jenkins-slave-base-centos7

# Install Docker
RUN yum install -y docker && \
    yum clean all -y

RUN chown -R 1001:0 $HOME && \
    chmod -R g+rw $HOME

USER 1001
