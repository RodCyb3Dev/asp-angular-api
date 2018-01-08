# ASP.NET Core Angular REST-API<br>
Using postman to test the api

# To Create API Backend Run<br>
$ Demo-ASP-Angular/>dotnet new webapi -o backend.api -n backend.api

To Run The App
$ dotnet run
Notic The App is Running in prod mode!

To Check the Environment Run<br>
$ $env:ASPNETCORE_ENVIRONMENT

To Change the Environment Run<br>
$ $env:ASPNETCORE_ENVIRONMENT="Development"<br>
$ export ASPNETCORE_ENVIRONMENT=Development (Works for Me!)

# To Create API Frontend<br>
In the same dir as the backend.api

$ ng new frontend OR ng new frontend --style=scss --routing
