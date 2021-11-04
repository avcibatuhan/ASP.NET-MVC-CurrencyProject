# ASP.NET MVC Currency Project <br/>

![UygulamaGörüntüleri-1](https://user-images.githubusercontent.com/43846788/140274168-bc7936ab-c676-4aa1-a5f1-717fd499f6f7.png)

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Code Examples](#codeExamples)
* [Screenshots](#screenshots)

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

4.Connect your SQL Server and Entity Framework <br/>

5.You should  Uncomment SaveSixMonthData() for <strong>ONCE!</strong> After that you must comment it <strong>AGAIN!</strong>

Because it's save to database last six month data just one time.When it's do that once, it doesn't need anymore. <br/>

![SaveSixMonth](https://user-images.githubusercontent.com/43846788/140272637-36db5e81-3afb-49f2-acbf-0e6ac9e112e1.png) <br/>

6.Run project once, when it's data scraping job done stop the project and don't forget comment the SaveSixMonthData() function. <br/>

7.Now project is ready!! <br/>

## Code Examples

* Fetching six month data with dynamic url:

![DynamicUrl (2)](https://user-images.githubusercontent.com/43846788/140276658-d6698997-52d3-4354-adc2-433cd7bfc060.png)

* Using Javascript get data from the Backend, filter json as a EUR,USD,GBP. Call draw graph function.

![karışıkDataGrafikPush](https://user-images.githubusercontent.com/43846788/140277668-4f2ae021-2799-49ff-85cf-7578f3ff38a6.png)

* Get weekly data from SQL Server on the backend and return JSON:

![WeeklyAllDataController](https://user-images.githubusercontent.com/43846788/140278050-27f37a7a-8ef8-4794-ba19-b0763dc8eb78.png)

## Screenshots

* EUR/TL, USD/TL, GBP/TL graphs

![3 ayrı veri](https://user-images.githubusercontent.com/43846788/140279706-1c03cf0c-ac84-4db4-a242-0a0e6a8a16a5.png)

* EUR/TL, USD/TL, GBP/TL in same graph

![3AylıkKarışıkData](https://user-images.githubusercontent.com/43846788/140279837-03fbb313-1111-4b00-b9f5-4d58d6e4ebc1.png)

* EUR/USD Graph

![eurUSDGrafik](https://user-images.githubusercontent.com/43846788/140279982-0efb920c-b52a-4a27-b616-83ff16a30773.png)


Have Fun!!



