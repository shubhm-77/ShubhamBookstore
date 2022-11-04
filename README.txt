3rd November 2022
1552
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
Added the additional stylesheets -
    <link rel="stylesheet" href="https://cdn.datatables.net/1.10.16/css/jquery.dataTables.min.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/jqueryui/1.12.1/jquery-ui.min.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/toastr.js/latest/css/toastr.min.css" />
and scripts -
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jqueryui/1.12.1/jquery-ui.min.js"></script>
    <script src="https://cdn.datatables.net/1.10.16/js/jquery.dataTables.min.js"></script>
    <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/toastr.js/latest/js/toastr.min.js"></script>
    <script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>
    <script src="https://kit.fontawesome.com/e19c476714.js"></script>
    from the CSS_JS.txt file in _Layout.cshtml
Added a dropdown to the Navbar in Views/Shared/_Layout.cshtml
                                <a class=" nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Content Management</a>
                                <div class=" dropdown-menu" sria-labelledby="navbarDropdown">
                                    <a class="dropdown-item" href="#">Action</a>
                                    <a class="dropdown-item" href="#">Another action</a>
                                    <div class="dropdown-divider"></div>
                                    <a class="dropdown-item" href="#">Something else here</a>
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