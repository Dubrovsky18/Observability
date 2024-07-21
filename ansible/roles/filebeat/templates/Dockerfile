FROM elastic/filebeat:8.14.3
USER root
RUN mkdir -p /var/log/filebeat
RUN chown -R filebeat:filebeat /var/log/filebeat
COPY --chown=root:filebeat ./config/filebeat.yml /usr/share/filebeat/filebeat.yml