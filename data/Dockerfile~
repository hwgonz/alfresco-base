# Data Volume Container for Alfresco and Postgres
FROM scratch
MAINTAINER Howard A. Gonzalez C. <hgonzalez@gr3000.com>
# Executables this small
# Thanks to tianon
# Haiku by way of credit
# https://github.com/tianon/dockerfiles
COPY true-asm /bin/echo
VOLUME ["/var/lib/postgresql"]
ENTRYPOINT ["/bin/echo"]
