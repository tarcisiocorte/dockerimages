FROM mcr.microsoft.com/dotnet/sdk:3.1
COPY --from=mcr.microsoft.com/dotnet/sdk:5.0 /usr/share/dotnet /usr/share/dotnet
RUN dotnet tool install Nuke.GlobalTool --tool-path /usr/local/bin
