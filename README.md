1. Open the .sln file in Visual Studio and Make sure  .Net core 3.1 is installed on the machine
2.Connect to the  SQL Server and make sure you are able to connect to 'Server=(localdb)\\mssqllocaldb' . If not able to access , then create a new SQL server connection and paste the connection string in appettings.json file in the project.
3. Go to Tools-> Nuger Package manager->Package manager console and in the console type below commands in sequence 
a) Add-Migration-Initial
b) Update-database
4. Run the project using IIS Express


