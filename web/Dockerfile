#######################
#dockerfile for webapp#
#######################

FROM microsoft/iis

RUN powershell -NoProfile -Command Remove-Item -Recurse C:\inetpub\wwwroot\*

COPY GameStore/* C:\GameStore

WORKDIR C:\GameStore