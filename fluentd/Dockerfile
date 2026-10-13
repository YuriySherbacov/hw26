FROM fluent/fluentd:v1.16-debian-1
USER root
RUN gem install fluent-plugin-elasticsearch -v 5.2.5 --no-document
USER fluent
COPY fluent.conf /fluentd/etc/fluent.conf
