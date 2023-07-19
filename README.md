# Angular ASP.NET Core Project

This project provides an example of getting started using ASP.NET Core and Angular together in VS2022.

The project has the following goals:

* Keep the Angular project code completely separate from the ASP.NET Core code to make updates of either technology easier in the future. This was a key consideration when organizing the folders/files in the project.

* Provide a way to serve an Angular application using an MVC view (you can easily change this to serve from a Razor Page as well).

* Allow standard MVC controllers/views to be used in situations where part of the application runs outside of Angular.

* Support running the Angular project completely separate from the ASP.NET Core Web API if desired (CORS is enabled in the Startup.cs project). See the notes below if you want to use this option.


