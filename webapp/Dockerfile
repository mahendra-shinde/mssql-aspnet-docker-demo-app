FROM microsoft/aspnetcore:1.1.11-nanoserver-sac2016

COPY . /app

WORKDIR /app

RUN ["dotnet", "restore"]

RUN ["dotnet", "build"]

EXPOSE 80/tcp


