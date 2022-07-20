FROM registry.access.redhat.com/ubi8:8.0

RUN yum --disableplugin=subscription-manager update && yum --disableplugin=subscription-manager -y install python3 && yum clean all -y

COPY mailer.py .
CMD bash -c "while true; do echo sleeping; sleep 5; done"
