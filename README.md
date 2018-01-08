# ASP.NET Core Angular REST-API
# Using Postman to test the api.

# 1. To Create API Backend Run<br>
$ Demo-ASP-Angular/>dotnet new webapi -o backend.api -n backend.api

To Run The App<br>
$ dotnet run<br>
Note the App is Running in prod mode!

To Check the Environment Run<br>
$ $env:ASPNETCORE_ENVIRONMENT

To Change the Environment Run<br>
$ $env:ASPNETCORE_ENVIRONMENT="Development"<br>
$ export ASPNETCORE_ENVIRONMENT=Development (Works for Me!)

# 2. To Create API Frontend<br>
In the same dir as the backend.api

$ ng new frontend OR ng new frontend --style=scss --routing
