FROM mcr.microsoft.com/dotnet/aspnet:10.0
WORKDIR /app
LABEL org.opencontainers.image.source="https://github.com/cbrzilla/JC_Budgeting_Umbrel"
LABEL org.opencontainers.image.description="JC Budgeting Server for Umbrel"
ENV ASPNETCORE_URLS=http://0.0.0.0:5099
ENV JCBUDGETING_SERVER_DATA_DIR=/data
EXPOSE 5099

COPY ./container/publish/ /app/

ENTRYPOINT ["dotnet", "/app/JCBudgeting.Server.dll"]
