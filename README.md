# DogApi

DogApi is a .net core 3.1 Api.

## Installation
Check into the appsettings.json the DefaultConnection
 (localdb) SQL SERVER:
 ```bash
 "Server=(localdb)\\mssqllocaldb;Database=aspnet-BreedsDogDB-7BE9FC14-E3E1-4D30-B471-E5414EE5E2FD;Trusted_Connection=True;MultipleActiveResultSets=true"
 ```
 OR IF YOU HAVE SQL SERVER NEED THIS:
```bash
 "DefaultConnection": "Data Source=.;Initial Catalog=BreedsDogDB;Integrated Security=True"
 ```
Use the migration commands 

```bash
* Add-Migration Initial
* Update-Database
```
## Run from POSTMAN
VERBS:
* Get: https://localhost:44382/api/breeds
* Post: https://localhost:44382/api/breeds 

choose Body, row and Format JSON 
in the Body row 
```
{
    "name":"testu"
}
```

## Usage

Manage all Breeds for dogs

## Contributing

Please make sure run Update-Database. 
And check throw  VS the SQL Server Object Explorer Database.
If can not find go to menu->View and choose SQL Server Object Explorer.

## License
