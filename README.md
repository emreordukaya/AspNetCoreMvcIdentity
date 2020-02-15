# AspNetCoreMvcIdentity

Updated with ASP.NET Core 3.1 

1) Download or clone project from Github

2) Setup "ConnectionStrings" paramate in "appsettings.sjon" file

3) Create tables to databese
From Dot net Console;
dotnet tool install --global dotnet-ef  (install dotnet-ef, if haven't)
dotnet ef database update  (install database)

4) Setup "SendGridKeyName" paramate in "appsettings.sjon" file
Go to SendGrid website (https://sendgrid.com/) and create acount then get "SendGridUser" and "SendGridKey".
Then fill them to "appsettings.sjon" file.
Then change "< ApiKey Name >" in Startup.cs file 
Then change "mail@domain.com" with your SendGrid acount email in EmailSender.cs file.