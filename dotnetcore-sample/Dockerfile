FROM microsoft/dotnet:latest

# Set the Working Directory
WORKDIR /app

# Copy the app
COPY . /app

# Tell .net core which port to expose
#ENV ASPNETCORE_URLS=http://*:80
EXPOSE 80/tcp

# Start the app
ENTRYPOINT dotnet dotnetacilx.dll
