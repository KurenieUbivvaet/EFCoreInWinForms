# Manual
WARNING!!! use SQL Server Express https://go.microsoft.com/fwlink/?linkid=866658
install NuGet packages:
"Microsoft.EntityFrameworkCore.SqlServer and Microsoft.EntityFrameworkCore.Tools".
The next step is to specify the path to your project in the console, in my case it is ">> cd E:\MyProject\WinFormsApp2".
The third step prescribes the following command: "Scaffold-DbContext "Server=localhost\SQLEXPRESS;Database=NameDataBase;Trusted_Connection=True;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models"
!!!Instead of localhost and Goods, write your connection to the MsSQL database and its name!!! 