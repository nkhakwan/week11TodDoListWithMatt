# _ToDoList Two Tables Linking Practice_

#### _Epicodus Week11 thursday Practice Project_

#### By _**Matt Stroud**_  _**Khan Sahab**_

## Description

_A web site that allow usesrs to add items with description and allow them to be linked with different categories sitting in other table._

## Setup/Installation Requirements

1. Clone this repository from GitHub.
2. Open the downloaded directory in a text editor of your choice.
3. To install the REPL dotnet script, run dotnet tool install -g dotnet-script in your terminal.
4. Run the program with the commands dotnet restore, dotnet build, and dotnet run.
5. Database: `inventory_demo`
6. Table: 
CREATE TABLE `items` (
  `ItemId` int NOT NULL AUTO_INCREMENT,
  `Description` varchar(255) DEFAULT NULL,
  `CategoryId` int NOT NULL,
  PRIMARY KEY (`ItemId`)
) ENGINE=InnoDB AUTO_INCREMENT=7 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;
CREATE TABLE `categories` (
  `CategoryId` int NOT NULL AUTO_INCREMENT,
  `Name` varchar(255) DEFAULT NULL,
  PRIMARY KEY (`CategoryId`)
) ENGINE=InnoDB AUTO_INCREMENT=6 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;

## Known Bugs
 
None. All the basic requirements of Project are fulfilled
 
## Support and contact details

_Have a bug or an issue with this application? Email post_khan@yahoo.com_

## Technologies Used

* C#
* .NET Core
* ASP.NET Core MVC
* MSBuild
* Razor
* Git and GitHub

### Specs
| Spec | Input | Output |
| :------------- | :------------- | :------------- |
| **User can add items by clicking add new items** | User Input:"add description” | Output: " Description and category displayed" |
| **User can view a particular Item** | User Input:”click on the item” | Output: "All items displayed along with their categories" |


### License

This software is licensed under the MIT license.

Copyright (c) 2020 **_Khan Sahab and Matt Stround_**