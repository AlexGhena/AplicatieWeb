The application described below was developed using ASP.NET MVC CORE 6.0. It provides the following functionalities:

Products can be searched using the implemented search engine.
Products can be sorted in ascending/descending order by price/rating.
Registered members can view the store's products and add them to the shopping cart.
Registered members can leave comments and reviews on products.
Unregistered members can view the store's products, but if they want to place an order, they are redirected to create an account.
Contributors can add products to the site after admin approval.
Contributors can delete/modify the products they have added to the site.
Admins have complete access to the application, including changing user permissions.
Admins can create/delete/edit categories.
Admins have the authority to delete user comments.

For database I used the SQL Server provided by the framework.
In order to have photos in the app you have to manually upload them.
To run this project, you must have Entity Framework Core installed, it should be run from Visual Studio, and you need to update the database connection string in appsettings.json to test the application on your desired database.
