FROM mcr.microsoft.com/dotnet/aspnet:3.1

RUN apt update && apt upgrade -y
WORKDIR /app
COPY . /app

ENTRYPOINT ["dotnet", "KissLog.Backend.AspNetCore.dll"]
