MSSQL and C# (WinFormsApp)
==========================

Instructions on how to connect and configure a database in a C# project

Step One
========

Components used
---------------

- Install Sql server express (https://go.microsoft.com/fwlink/p/?linkid=2216019&clcid=0x409&culture=en-us&country=us)
- Create project Windows Forms (Microsoft)
- At the top of the project, find extensions -> manage extensions
- In the search bar, enter EF Core Power Tools 

Step Two
========

Database connections and code generation
----------------------------------------

- Right-click on the root file of the project and select EF Core Power Tools -> Rewers Engineer 
- Press Add -> Add Database connection
- In the Server name line, enter the name of our server, which can be taken from MSSQL and in the database connection section, select from the drop-down list or enter the database name
- Press ok and on the home page, press ok
- Chuse Database Objects (choose what interests you)
- In next window select next options: `Install the EF Core provider package in the peoject`, `Include connection string in genirated code` and optionally, you can specify folders for `Entity Types path` and `DbContext path`. Namespace change as desired.
- Press ok and well done...

Step Three
==========

Created our code...
-------------------