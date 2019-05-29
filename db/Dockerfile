######################
#dockerfile for mssql#
######################

FROM mcr.microsoft.com/mssql/server:2017-latest-ubuntu  

ENV ACCETP_EULA=Y
ENV SA_PASSWORD="P@ssw0rd"
ENV MSSQL_PID="Express"

MAINTAINER test

RUN apt-get update && systemctl enable mssql-server 

EXPOSE 1433

CMD ["--port 1433"]

ENTRYPOINT mssql-server 