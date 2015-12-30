##Simple Authentication

###Description
Simple registration app using ASP.NET 5, MVC 6, Entity Framework 6, Identity 3

###Use
Database needs to be created. Connects to localdb server. Run migrations with these commands in Command Prompt from project folder

        `dnvm use 1.0.0-rc1-update1`
        `dnx ef migrations add [MigrationName]`
        `dnx ef database update`