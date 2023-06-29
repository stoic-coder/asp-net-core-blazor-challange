# asp-net-core-blazor-challange
This coding challenge is for a .NET developer. We are assuming that you are familiar with .NET Core and REST.
There is a "Blazor" part included which should be on beginner level but for an experienced developer.

Your first task is to build an API (first project) that gives a list of ("GetAllBooks") books, so only one api-method is needed.
You should not use a database bat generate fake data with a existing library like https://github.com/bchavez/Bogus

Your second task is to build a simple blazor frontend(second project) which shows all books (from GetAllBooks) in a Grid.
There should only be one Page, no menu or logo or some other clutter just the pure grid, which can be sorted, filtered and grouped.

There is no strict time limit and you won't be judged on how long it took you to complete, however, we would like you to spend no more than 3 hours on this.

You must use .NET Core and C#
The API should be a ASP.NET Core Web API project
The API should consume and return data as JSON
The Api should be documented with swashbuckle

For the Blazor Grid you should use the free grid from https://razor.radzen.com/datagrid
You do not need to consider any security implications. This includes using HTTPS or attempting to provide any Authorization/Authentication
You do not need any persistent storage. 
You can use any NuGet package besides the listed ones but be prepared to justify its usage
We expect you to be mindful of correct HTTP status code usage

You should clone this repository and when you're ready to share your work push it to private repository and add me (stoic-coder) as a collaborator so I can check it out.

