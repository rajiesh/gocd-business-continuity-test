FROM postgres:9.6.5
ADD init-for-replication.sh /docker-entrypoint-initdb.d/
ADD init-vol.sh /docker-vol-entrypoint.sh

ENTRYPOINT ["/docker-vol-entrypoint.sh"]
