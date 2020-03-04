FROM bitnami/postgresql
ENV POSTGRESQL_USERNAME postgres
ENV ALLOW_EMPTY_PASSWORD yes
EXPOSE 5432
ENTRYPOINT ["/opt/bitnami/postgresql/bin/postgres","-D","/bitnami/postgresql/data"]
