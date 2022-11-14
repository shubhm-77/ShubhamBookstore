2022 November 3rd
3:52 pm
Started Assignment 2
Created New Project
Selected ASP.NET Core Web App(Model-View-Controller)
Named it ShubhamBookstore
next
Selected ASP.NET Core 3.0
Selected Individual Accounts
Created Successfully
Commented "sslPort": 44388 in launchSettings.json
Created Git Repository
named ShubhamBookstore
Created README.txt file
Ran Successfully
Registered Email and password
Successfully registered
Login successfully
Part 1.1 Review
complete
Part 1.2 Debugging
Added two breakpoints in HomeConroller.cs in IAction Index and Privacy 
ran it
Part 1.3 Bootstrap
Gone to Bootwatch.com
Selected a theme(Yeti)
Downloaded Bootstrap.css
Replaced existing Bootstrap.css in wwwroot/lib/bootstrap/dist/css
Replaced site.css file in wwwroot/css
Changed the file name from bootstrap.min.css to bootstrap.css in Views/Shared/_Layout.cshtml
Changed the nav class from navbar-light to navbar dark and bg-white to bg-primary
Removed text-dark in line 23 & 26
Added additional properties to the footer class
Removed references to text-dark
ran it to review changes
ran successfully

4:17 pm
Added the additional stylesheets and scripts
Added a dropdown to the Navbar in Views/Shared/_Layout.cshtml
Saved, Refreshed and Reviewed the UI
Changed Dropdown to Content management

4:47 pm
Setting up the Project(Part-1)
Part 1.4 Add Projects and Modify
Added three new projects (.NET Core class library) to the application:
ShubhamBooks.DataAccess
ShubhamBooks.Models
ShubhamBooks.Utility
Copied the Data folder and pasted it to .DataAccess project (deleted the original)
Installed Nudget packages
Deleted the Migrations folder
Installed Nudget Package
Modified the namespace to reflect the project
Deleted default Class1.cs file in all projects

5:29 pm
Build the project
Moved Models in ShubhamBooks.Models and deleted original
Modified Views/Shared/Error.cshtml
Added project reference .DataAccess and .Models
Renamed Models folder to ViewModels
Changed the ErrorViewmodels.cs namespace .Models.Viewmodels
Build the project

9:57 am
4th November 2022
Modified startup.cs by adding context with the using statement
Ran it to review errors
Failed
Removed the using statement
Corrected any default references to ErrorViewmodels to the .Models.ViewModels.ErrorViewmodels
Error in namespace

12:42pm
Removed 'options => options.SignIn.RequireConfirmedAccount = true'

2022 November 11th
1:41 pm
README updated

2022 November 12th
4:57 pm
Corrected mistake in HomeController.cs

5:06 pm
Corrected Error.cshtml
Ran it to review errors
Review the browser presentation

5:30 pm
Created static detailed class named SD.cs in the Utility project
Modified properties of class
Added project reference to the main project
Added project reference to Models and Utility in the DataAccess project
Added a Customers area to the Areas
Changed the routes in Startup.cs like the one outlined in the ScaffoldingReadMe.txt
Moved the HomeController.cs to the Area > Customer > Controller folder
Deleted Data and Models folder

2022 November 13th
11:23 pm
Edited the HomeController.cs to explicitly define that the controller is in the Customer Area
Moved Views>Home and modified the HomeController namespace
Ran the application....why?
Copied _ViewImports and _ViewStart to Customers Area
Modified ViewStart.cshtml to reflect the new path
Ran the application
Added a new Admin Area in Areas
Added the proper View files and deleted the Data and Models folder
Deleted the Controllers folder
modified spelling in HomeController.cs
Updated the Github Repos

2022 November 14th
10:30 am
Started part 2- Build the project
2.1 Create the DB
Build the application to check there are no errors
Reviewed appsettings.json
Created the migrations, modified the database and saved it.
Used the NuGet package Manager Console to add the migration
Wrong default project is selected
Changed to the correct default project (.DataAccess) and ran again
Added the new migration file name entry - 20221114164249_AddDefaultIdentityMigration.cs
Reviewed the file for the SQL
Noted the tables related to ASP.NET Identity
Updated the database
Reviewed the updated database in the SQL server
checked for errors 
ran it