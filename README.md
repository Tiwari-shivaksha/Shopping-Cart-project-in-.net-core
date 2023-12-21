here is no admin panel for adding products, I have directly added it to the database. I recommend you to follow the tutorial.

How to run it
clone the project git clone https://github.com/rd003/BookShoppingCart-Mvc

open appsettings.json file and update connection string

"ConnectionStrings": { "conn": "data source=your_server_name;initial catalog=MovieStoreMvc; integrated security=true;encrypt=false" }

Delete Migrations folder

Open Tools > Package Manager > Package manager console

Run these 2 commands

 (i) add-migration init
 (ii) update-database
Now you can run this project

How to register as admin and login??
Open the Program.cs file , you will find these commented lines

//{
//    await DbSeeder.SeedDefaultData(scope.ServiceProvider);
//} ```

Uncomment these line and run the project. Now stop the project and comment these lines again.

Now click on login and login with these credentials. username: admin@gmail.com , password: Admin@123
About
Source code of BookShoppingCart app created in mvc

Resources
 Readme
 Activity
Stars
 10 stars
Watchers
 2 watching
Forks
 10 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
C#
76.4%
 
HTML
23.2%
 
CSS
0.4%
Footer
