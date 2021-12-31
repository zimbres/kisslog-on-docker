FROM mcr.microsoft.com/dotnet/aspnet:3.1

RUN apt update && apt upgrade -y
RUN apt install libgdiplus -y
WORKDIR /app
COPY . /app

ENTRYPOINT ["dotnet", "KissLog.Frontend.AspNetCore.dll"]
