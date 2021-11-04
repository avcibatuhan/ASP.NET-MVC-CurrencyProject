# ASP.NET MVC CurrencyProject

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This project is made using technologies like C#,ASP.NET MVC,JavaScript,HTML5,CSS3,Entity Framework.
 
This project created for the get last six month Dollar,Euro and Sterling data from the [TCMB(Turkish Central Bank)](https://www.tcmb.gov.tr/kurlar/today.xml) and save it to the your SQL server. Client side use this data and draw a lot graphs (Eur/Usd,Eur,Dollar,Sterling etc.)
	
## Technologies
Project is created with:
* Visual Studio version: 2019
* Bootstrap version: 3.4.1
* Jquery library version: 3.4.1
* Entity Framework version: 6.0.0
* SQL Server 2014
	
## Setup

1. Open `Dovizkurlari.sln` with Visual Studio.
2. Create a database table like this 
![Veritabanı Tablo Görünümü](https://user-images.githubusercontent.com/43846788/140271661-62428775-2566-481d-ba66-8f62c9e51989.png)
3.Example TCMB XML data
![TCMBkaynakKod](https://user-images.githubusercontent.com/43846788/140272171-3d70b3f2-26d8-4e26-8e12-ffce63278cd5.png)
4.You should <h1>Uncomment SaveSixMonthData for ONCE ! </h1>
![SaveSixMonth](https://user-images.githubusercontent.com/43846788/140272637-36db5e81-3afb-49f2-acbf-0e6ac9e112e1.png)
