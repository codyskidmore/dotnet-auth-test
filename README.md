# dotnet-auth-test
### .NET 8 Auth Reference

#### Use the following commands to run the project.

#### Postman tests are included.

```shell
cd /src/auth-test
dotnet restore
dotnet ef migrations add InitialCreate
dotnet ef database update

dotnet run
```