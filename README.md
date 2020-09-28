# **JobTo** - Ticket Management System
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)
[![N|ASP.NET Core 3.0](https://i.ibb.co/rM1ds8y/dot-net-core-angular.png)](https://docs.microsoft.com/en-us/aspnet/core)


![Build and deploy ASP.Net Core app to Azure Web App - jobtoapi](https://github.com/osnipezzini/jobto/workflows/Build%20and%20deploy%20ASP.Net%20Core%20app%20to%20Azure%20Web%20App%20-%20jobtoapi/badge.svg)

JobTo is software that comes with the idea of helping support companies to control the attendance of tickets and products sold.

- Registration of products, services, customers, companies and more.
- Opening of tickets can be done by both the customer and the technician, with fully customizable permissions by company, group of companies, groups of customers and much more.

## This application consists of:

*   Template pages using Angular 9 and TypeScript
*   RESTful API Backend using ASP.NET Core 3.1 MVC Web API
*   Database using Entity Framework Core
*   Authentication based on OpenID Connect
*   API Documentation using Swagger
*   Angular CLI for managing client-side libraries
*   Theming using Bootstrap 4

## You get the benefits of:

*   A complete backend and frontend project structure to build on, with login, user and permission-based role management already integrated
*   Data Access Layer built with the Repository and Unit of Work Pattern
*   Code First Database
*   A RESTful API Design
*   Angular Directives Quidance
*   Angular Pipes Quidance
*   Angular Animations Quidance
*   Angular Services
*   Dialog and Notification Services
*   Configuration Page and Configuration Service
*   Integrated Internationaliztion
*   Theming with SASS
*   Ready-to-use email API
*   Handling Access and Refresh Tokens with WebStorage (Bearer authentication) - No Cookies
*   Jquery Integration (Ability to use standard Jquery libraries)
*   CRUD APIs
*   Responsive Design
*   Etc.


## Installation

*   Clone the [Git Repository](https://github.com/osnipezzini/jobto.git) and edit with your favorite editor. e.g. Visual Studio, Visual Studio Code

## Installation Notes

*   When creating a new project please wait for all dependencies to be restored; "dotnet restore" for asp.net project & "npm install" for angular project.
    When using VisualStudio this is automatic, check the output window or status bar to know that the package/dependencies restore process is complete before launching your program for the first time.
*   If you get any errors, consider running manually the steps to build the project and note where the errors occur.
    Open command prompt and do the below steps:  
    1. run 'dotnet restore' from the two project folders - Restore nuget packages
	2. run 'npm install' from the project with package.json - Restore npm packages
	3. Try running the application again - Test to make sure it all works
*	When running the client(angular) project on a different address/domain from the backend, configure the baseUrl of the client to match that of the server.
	You do this from environment.ts in the ClientApp/Angular project.
	Example: baseUrl: "http://yourbackendserver.com" OR baseUrl: "http://localhost:5050"
*	For bug reports open an [issue on github](https://github.com/osnipezzini/jobto/issues)


## Login

LOGIN WITH USERNAME OR EMAIL ADDRESS
> * **Default Administrator Account**
>   * Username: admin
>   * Email:    admin@jobto.com
>   * Password: Admin@123
> * **Default Standard Account**
>   * Username: user
>   * Email:    user@jobto.com
>   * Password: User@123


## Documentation

*   [Conceptual overview of what is ASP.NET Core](https://go.microsoft.com/fwlink/?LinkId=518008)
*   [Working with Data](https://docs.microsoft.com/en-us/ef/#pivot=efcore)
*   [Angular 9 documentation overview](https://angular.io/guide/quickstart)
*   [Getting started with Angular CLI](https://cli.angular.io)
*   [Introduction to Bootstrap 4](https://getbootstrap.com/docs/4.1/getting-started/introduction)
