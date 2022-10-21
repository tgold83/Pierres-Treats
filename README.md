# _Pierre's Treats_

#### By _Ted Gold_

#### _An MVC project that allows the user to put in flavors and treats and assign them to each other using a many to many coneection._

## Technologies Used

* _C#_
* _.Net_
* _Enitity_
* _MySQL_
* _Identity_

## Description

_A simple MVC application where the user can input as many different Treats as they like. The Treat takes in a name. Then for each treat, they can add as many flavors to them as they like. A Flavor takes in a description. The user can add, delete, and update flavors and treats and see a list of all cof them. Also, this project allows users to sign in using an email and a pasword. If the user is logged in they can utilize all of the features of the application. If they are not signed in, they will only have read capabilities._

## Setup/Installation Requirements

* _Clone the repository using $git clone._
* _Open the project using $code ._
* _Build the project using $dotnet build._
* _Create a file called appsettings.json in the directory of your project's production folder, Pierres-Treats_
* _Add this line of code to appsettings.json file:_
  {
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=schedule;uid=root;pwd=[YOUR-PASSWORD-HERE];"
    }
  }
* _Put your password for My SQL Workbench in the section that reads [YOUR-PASWORD-HERE]_
* _Update the database with $dotnet ef database update_
* _Run the program with $dotnet run._

## Known Bugs

* _No known bugs_

## License

_MIT License_

_Copyright (c) [2022] [Ted Gold]_

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

Copyright (c) _2022_ _Ted Gold_