# CalenderBasic
Docker requirement:
1. docker pull mcr.microsoft.com/mssql/server:2017-latest
2. docker run -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=P@ssw0rd' -p 1400:1433 -d mcr.microsoft.com/mssql/server:2017-latest
3. Azure Data Studio: New connect -> sa + password -> Advanced port : 1400