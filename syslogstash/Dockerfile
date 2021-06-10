ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}

# User root to read docker system logs
USER root

# WORKDIR /usr/share/logstash

# Copy with permissions
# See logstash.conf for destination folder 
# COPY --chown=logstash:logstash testlogs logs2ES

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
