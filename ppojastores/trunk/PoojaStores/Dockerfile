FROM mcr.microsoft.com/dotnet/aspnet:3.1 
WORKDIR /app
ADD ./publish /app
RUN dotnet build
EXPOSE 80
ENTRYPOINT ["dotnet", "run", "--urls", "http://0.0.0.0:80"]
