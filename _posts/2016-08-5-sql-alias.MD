---
layout: post
title:  "SQL Alias"
date:   2016-08-6 11:00:00 +0800
categories: SQLServer sql alais
---

I recently had a problem to create a SQL Server alias and tried many things to solve it. Here is my complete the solution if you want to enable SQL Server.

1. Open SQL Server Configuration Manager. If you cannot find it in the Windows application menu, run this command: `C:\Windows\SysWOW64\mmc.exe /32 C:\Windows\SysWOW64\SQLServerManager12.msc`
Note that the number 12 could be different based on your SQL Server version.

2. Browse to the SQL Native Client XX.X Configuration where X.XX is your SQL Server version. Add the alias with required name as shown in the picture below:
![SQL Server Configuration Manager](http://mzaatar.github.io/images/SQLServerAliasPost/SQLServerConfig.png "SQL Server Configuration Manager")

3. Make sure that the SQL following Server services are running: SQL Server, SQL Server Browser, SQL Server Agent as below:
![SQL Server Services](http://mzaatar.github.io/images/SQLServerAliasPost/SQLServerServices.png "SQL Server Services")

4. Here is the trick to make sure that it is running, open SQL Server Client Network utility by open the Windows Command run and type `CLICONFG`.

5. In general tab, enable the  TCP/IP and named pipes protocols as following picture:
![SQL Server Client Network Utility general tab](http://mzaatar.github.io/images/SQLServerAliasPost/SQLServerClientNetworkUtility_1.png "SQL Server Client Network Utility general tab")

6. In alias tab, add the required alias as following:
![SQL Server Client Network Utility alias tab](http://mzaatar.github.io/images/SQLServerAliasPost/SQLServerClientNetworkUtility_2.png "SQL Server Client Network Utility alias tab")

Enjoy SQL Server Alias!