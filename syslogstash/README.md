### Sys-logstash
Send docker logs to ES

- To mount docker log folder to container, go to .env and set $LOG_SRC_DIR 

- Match log filename in logstash.conf

- In docker-compose.yml, to prevent flooding ES with own messages, 
set logging to none.

- Filter logs e.g. stream:stderr in Kibana
