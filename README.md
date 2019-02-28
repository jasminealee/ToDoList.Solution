## | **To-Do List Project** |

#### By Jasmine Lee and Marie Dillard
###### The To-Do List Project February 28, 2019 ######
----------

## Description
A simple to-do list program that allows users to add items, view the list, and clear the list.

## Known Bugs
* No known bugs.

## Specifications

| Behavior | Input | Output |
|----------|:-----:|:------:|
| Item on list can be created | New Item | (Item Exists) |
| Program returns description of item | New Item: "Walk dog" | "Walk dog" |
| User can view list of items added | View | Return list |
| List is returned numbered | View | Return numbered list |
| Clear list option | Clear | List is emptied |
| User can return to menu | Return | Main menu appears |
| Program cycles through options of add, view, clear, return to menu | User answer to return to menu: Y | Return to menu |

## Setup and Use

#### Prerequisites
* .NET Core 1.1 SDK or higher
* .NET Core Runtime 1.1 or higher
* [Mono](https://www.mono-project.com/)

#### Download Repo
1. Download required software: .NET Core SDK, .NET Core Runtime, Mono
2. Clone [this repository](https://github.com/LondresRi/ToDoList.Solution): _$ git clone (repo HTTPS)_

#### Open Locally
1. Navigate to the working directory: _$ cd ToDoList.Solution_
2. Use your preferred IDE or editor to edit the project
3. Open the Program.exe file or use _$ mono Program.exe_ to run application

#### Compile Locally
1. Navigate to the project directory: _$ cd ToDoList.Solution/ToDoList_
2. Execute _$ mcs Program.cs Models/Item.cs_ to compile new Program.exe file

#### Test Locally
1. Navigate to the working directory: _$ cd ToDoList.Solution/ToDoList.Tests_
2. Execute _$ dotnet tests_ to run application tests

## Built With

* Linux Fedora 29
* Atom (IDE)
* C#
* .NET Core 2.0
* GitBash

## Contributors

| Author | GitHub | Email |
|--------|:------:|:-----:|
| Jasmine Lee | [jasminealee](https://github.com/jasminealee) | [jasmine.a.l1722@gmail.com](mailto:jasmine.a.l1722@gmail.com) |
| Marie Dillard | [milkybot](https://github.com/milkybot) | [mariedillard@protonmail.com](mailto:mariedillard@protonmail.com) |

## Support and contact details

If you have any feedback or concerns, please contact

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Copyright (C) 2019 Jasmine Lee and Marie Dillard. All Rights Reserved.

MIT License

Copyright (c) 2019 Jasmine Lee and Marie Dillard
