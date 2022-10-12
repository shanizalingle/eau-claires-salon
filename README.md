# _Eau Claire's Salon_

#### By _**Shaniza Lingle**_

#### _Help Claire manage her employees (stylists) and their clients._

## Technologies Used

* _C#_
* _.NET_
* _mySQL_
* _HTML_
* _CSS_
* _Entity_


## Description

_Claire can add a list of stylists working at the salon, and for each stylist, add clients who see that stylist. The stylists have specific specialties, so each client can only see (belong to) a single stylist._


![screenshot](https://raw.githubusercontent.com/shanizalingle/eau-claires-salon/main/HairSalon/wwwroot/img/screenshot.webp)


## Setup/Installation Requirements

* _In your terminal enter, "git clone https://github.com/ShanizaLingle/eau-claires-salon"_
* _Open the directory in Visual Studio Code_
* _In VS Code terminal, navigate to the HairSalon directory_ 
* _In VS Code terminal, configure files with the following_

```json

$ dotnet add package Microsoft.EntityFrameworkCore -v 5.0.0

```
```json

$ dotnet add package Pomelo.EntityFrameworkCore.MySql -v 5.0.0-alpha.2

```

* _In VS Code terminal, install Lazy Loading with the following_

```json

 $ dotnet add package Microsoft.EntityFrameworkCore.Proxies -v 5.0.0

```
* _In VS Code terminal, run " $ dotnet restore "_
* _Create file names "appsettings.json"_
* _Enter the following into the file_

```json
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=shaniza_lingle;uid=root;pwd=YOUR_PASSWORD;"
  }
}
```
* _For database setup, open MySQL and navigate to 'Administration' > 'Data Import'_
* _Check 'Import from self contained file' and enter the file path of the Database within HairSalon, then start Import_
* _In VS Code terminal, to start application run " $ dotnet run "_

## Known Bugs

* _No known bugs_

## License


_[MIT](https://en.wikipedia.org/wiki/MIT_License)_

Copyright (c) _2022_ _Shaniza Lingle_