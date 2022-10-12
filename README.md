# _Eau Claire's Salon_

#### By _**Shaniza Lingle**_

#### _Help Claire manage her employees (stylists) and their clients.._

## Technologies Used

* _C#_
* _.NET_
* _mySQL_
* _HTML_
* _CSS_
* _Entity_


## Description

_Claire can add a list of stylists working at the salon, and for each stylist, add clients who see that stylist. The stylists have specific specialties, so each client can only see (belong to) a single stylist._

![alt text](https://github.com/shanizalingle/eau-claires-salon/tree/main/HairSalon/wwwroot/img/hair.jpeg?raw=true) 


## Setup/Installation Requirements

* _In your terminal enter, "git clone https://github.com/ShanizaLingle/eau-claires-salon"_
* _Open the directory in Visual Studio Code_
* _In VS Code terminal, navigate to the HairSalon directory_ 
* _In VS Code terminal, configure files with the following_

```json
  $ dotnet add package Microsoft.EntityFrameworkCore -v 5.0.0' & '$ dotnet add package Pomelo.EntityFrameworkCore.MySql -v 5.0.0-alpha.2
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

_MIT License_

_Copyright (c) [2022] [Shaniza Lingle]_

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Copyright (c) _2022_ _Shaniza Lingle_