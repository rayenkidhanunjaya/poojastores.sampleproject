FROM mcr.microsoft.com/dotnet/aspnet:3.1 
WORKDIR /app
COPY . /app
RUN cp -R ./publish/* /app
RUN dotnet build
EXPOSE 80
ENTRYPOINT ["dotnet", "run", "--urls", "http://0.0.0.0:80"]
