# Asp.Net Core with React.js


## Instructions to create this project
1-  Open visual studio 2022

2-  Select "create a new project" option

3-  Search "react.js" template and select "ASP.NET Core with React.js"

4-  Enter project name like "MyReactProject" and chose location

5-  On next window chose framework as ".NET 6.0" and Authentication type as "Individual Accounts"

6-  After creating the project install a nuget package named "Microsoft.VisualStudio.Web.CodeGeneration.Design" with version 6.0.6

7-  Right click on your project and select "Add" then select "New Scaffolded Item"

8-  On new window select "Identity" from left pane and click on "Add" button to add Identity scaffolding

9-  Another new window will open from there select all check boxes by selecting the option "Override all files" and on bottom select "ApplicationDbContext" for data context class dropdown then click on "Add" button.   (by doing this it will create all identity's mvc pages)

10- Open Nuget package console to to run "add-migration" and "update-database" command to add database


## That's it. You are done.
Now you can run your .net project only then it will start the reactjs ClientApp within .Net project


# NOTE::
If you found "Data" named folder under **Area/Identity/Data** then remove that folder from the project and build the project then run the project.
