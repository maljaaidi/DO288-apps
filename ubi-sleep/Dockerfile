FROM registry.access.redhat.com/ubi8:8.0

RUN yum install -y --disableplugin=subscription-manager python3 && yum clean all -y --disableplugin=subscription-manager

COPY mailer.py .
CMD bash -c "while true; do echo sleeping; sleep 5; done"
