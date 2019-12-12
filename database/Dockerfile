FROM postgres:10-alpine
USER postgres
ADD pg_hba.conf /usr/share/postgresql/9.6/
ADD postgresql.conf /usr/share/postgresql/9.6/
ADD init-db.sql /docker-entrypoint-initdb.d
