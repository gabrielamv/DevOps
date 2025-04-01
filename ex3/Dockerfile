# Am folosit imagine de postgrees
FROM postgres:14

#variabilele de mediu luate din .env
ENV POSTGRES_USER=${POSTGRES_USER}
ENV POSTGRES_PASSWORD=${POSTGRES_PASSWORD}
ENV POSTGRES_DB=${POSTGRES_DB}

#volum persistent
VOLUME ["/var/lib/postgresql/data"]

EXPOSE 5432

#rulam postres
CMD ["postgres"]

