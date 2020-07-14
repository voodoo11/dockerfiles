FROM python:3

ENV DEBIAN_FRONTEND=noninteractive

RUN apt -qq update && \
    apt -yqq install krb5-user && \
    apt -yqq clean

CMD ["cat", "/etc/krb5.conf"]