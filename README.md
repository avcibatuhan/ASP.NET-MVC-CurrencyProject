# ASP.NET MVC CurrencyProject

![UygulamaGörüntüleri-1](https://user-images.githubusercontent.com/43846788/140274168-bc7936ab-c676-4aa1-a5f1-717fd499f6f7.png)

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

1. Open `Dovizkurlari.sln` with Visual Studio. <br/>
2. Create a database table like this <br/>
![Veritabanı Tablo Görünümü](https://user-images.githubusercontent.com/43846788/140271661-62428775-2566-481d-ba66-8f62c9e51989.png) <br/>
3.Example TCMB XML data <br/>
![TCMBkaynakKod](https://user-images.githubusercontent.com/43846788/140272171-3d70b3f2-26d8-4e26-8e12-ffce63278cd5.png) <br/>
4.You should  Uncomment SaveSixMonthData for <strong>ONCE!</strong> After that you must comment it <strong>AGAIN!</strong>
Because its save last six month data just one time.When it's do that once, it doesn't need anymore. <br/>
![SaveSixMonth](https://user-images.githubusercontent.com/43846788/140272637-36db5e81-3afb-49f2-acbf-0e6ac9e112e1.png) <br/>
5.Run project once, when it's data scraping job done stop the project and don't forget comment the SaveSixMonthData() function. <br/>
6.Now project is ready!! <br/>
