
# System Requirements

## Application Server / VM  

- Windows Server 2012+
- .NET Framework 4.8 (If you need to install the Designer on the Application Server)
- [ASP.NET Core Runtime 8.x.x Windows Hosting Bundle](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- PowerShell 7
- IIS installed (see list of enabled features below)

<br/>

## Infrastructure

- Azure Service Bus subscription
- alternatively, RabbitMQ for on-prem deployments without internet access

<br/>

## Database

- On-prem deployment: SQL Server 2019 Standard or higher
- Azure deployment: Azure SQL Database

<br/>

## Client (End user)

- Microsoft Edge, Chrome, Firefox, Opera, Safari

<br/>

## InVision Designer (Developer)

- Windows 10, Windows Server 2012 or later
- .NET Framework 4.8

___
## Minimum hardware requirements

Hardware should be scaled based on the needs for every installation. The figures below are general minimum requirements. It’s technically possible to run everything on one server (Application and Database), but not recommended for performance reasons.

<br/>

## Application Server

- CPU: 4 Cores
- Memory: 8 GB
- Disk Space: 50 GB

<br/>

## SQL Server

- CPU: 4 Cores (Faster is better)
- Memory: 16 GB
- Disk Space: 500 GB

<br/>

## IIS Required Features
<br/>

**IIS Enabled Features**
![IIS](https://profitbasedocs.blob.core.windows.net/images/req1.jpg)
<br/>

![IIS](https://profitbasedocs.blob.core.windows.net/images/req2.jpg)

<br/>

## See Also  
* [System Description](systemrequirements/systemdescription.md)
  
<br/>