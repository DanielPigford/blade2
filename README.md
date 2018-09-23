# blade2 - Shaping Source Code - a code generation tool with Handlebars

BLADE2 - A console utility developed in NodeJS using Visual Studio Code on macOS.  The initial goal of the project is to use SQLClient and Handlebars.Net libraries to construct generated program source code for data access.  Ultimately Blade2 will be able to generate any type of source code the template references.  Blade2 is a developer tool that shapes source code, saves time, and reduces bugs.

> usage: $> blade2 {config.json}

## Who makes Blade2?  Can I help with the development?

Daniel Pigford, you can find me on GitHub as DanielPigford.  Feel free to pass along _any_ feedback or suggestions for Blade2.

## What development tools are used to build Blade2?

For the development of BLADE2 I use Visual Studio Code (macOS), .NET Core 2.0, Handlebars.Net and Json.NET.

* Visual Studio Code: https://code.visualstudio.com
* NodeJS: 
* HandlebarsJS: 

## Why use NodeJS?

Write once, run anywhere that NodeJS runs. (Windows, macOS, Linux)

## What is Blade2?

Blade2 was created to answer a need to generate data access class source code in software projects using the Database First generation approach.  Database First means the database either exists or is created prior to building the application and referenced to create source code patterns.  The long term goal is to make blade2 compatible with SQL Server, MySQL, Postgres, SQLite and Oracle databases.

The original data access templates that the Blade2 utility uses were first developed by Daniel for another generation tool that has since been retired.  The Blade2 utility replaces that previous tool.  https://my2ndgeneration.wordpress.com/2014/03/20/xojo-mybackspace-and-m2g/

The source code for Blade2 is available on GitHub.  https://github.com/DanielPigford/blade2/

## Why is it called Blade2?

Blade2 is named after devices with ultra fine edges used for cutting, shaping and carving.  We use Blade2 to build/shape/cut/create source code using Handlebar templates and database schema information.

## What Handlebar Templates are available for Blade2?

There is a growing list of template groups available.

* razor - Data access templates for .NET Core, .NET Framework and JavaScript.  100% source code, no assemblies required.
* switch - Development and management templates for TSQL.
* docs - Documentation templates for TSQL.

## Will you be making more templates?

Yes.

## Where are the templates hosted?

The Handlebar templates are currently hosted on GitHub.  The repository is public and we are accepting requests to help with our development process.

* razor:  https://github.com/DanielPigford/razor
* switch: https://github.com/DanielPigford/switch 

## Can I make my own templates?

Yes.  Many people do for coding templates, snippets and libraries.

## What does Blade2 do?

Blade2 generates source code files based on Handlebar templates using database schema definition information as input into the template generation process.

## How do I use Blade2 in my project?


