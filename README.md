# Hosting WCF service with netTcpBinding or netNamedPipeBinding in IIS
This article describes your necessary actions to host your WCF services with netTcpBinding or netNamedPipeBindings in IIS. 
IIS supports HTTP or HTTPS protocols by default however to use netTcpBindings or netNamedPipeBinding you need to manage some settings in IIS.

## Project

1. [Northwind WCF Service](https://github.com/geeksarray/hosting-wcf-service-with-nettcpbinding-or-netnamedpipebinding-in-iis/tree/main/Northwind%20Services/NorthwindServices) -
   with netTcpBinding and netNamedPipeBinding exposed.
  
1. [NorthwindHost](https://github.com/geeksarray/hosting-wcf-service-with-nettcpbinding-or-netnamedpipebinding-in-iis/tree/main/Northwind%20Services/NorthwindServices)  - windows 
   installer to host WCF Services.
   

For netTcpBinding or netNamedPipeBinding in WCF you will have to make some settings in Windows Services like

![Hosting WCF service with netTcpBinding or netNamedPipeBinding in IIS](https://geeksarray.com/Images/blog/Services.png)

For more detailed description please visit - https://geeksarray.com/blog/hosting-wcf-service-with-nettcpbinding-or-netnamedpipebinding-in-iis


