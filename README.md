# SSD

## Synopsis

The **SSD** application revolutionized our deployment process.
It reduced the process execution time from two weeks and a lot of documentation to **under 5 minutes** and **zero documentation**.

SSD allows the release manager to copy application components from a source environment to a destination environment, ie, from development to testing or from testing to production.

Currently the supported components are:

* Databases;
* Web applications;
* ETL packages;
* Cubes;
* Reports.

SSD was developed with the following stack:
* [AngularJS](https://angularjs.org)
* [Bootstrap](http://getbootstrap.com)
* [WebAPI](http://www.asp.net/web-api)
* [SQL Server](https://www.microsoft.com/en-us/cloud-platform/sql-server)

## Screenshots

### Main

The main page is composed by:
* a navigation toolbar and the profile picture of the user (fetched from our Active Directory);
* an awesome automation robot which caused the application to be know as **Ninja**;
* a timeline of deployments and their status: new, in progress, approved, deploying, success, error.

![main](https://github.com/rmgpinto/ssd/blob/master/main.jpg)

### Add component

Adding a component is as easy as:

1. Selecting it's type;
2. Filling the information (first image): source server, source component, destination data sources and destination server;
3. Waiting a few seconds for feedback (second image).

![add component](https://github.com/rmgpinto/ssd/blob/master/add%20component.jpg)
![add component feedback](https://github.com/rmgpinto/ssd/blob/master/add%20component%20feedback.jpg)

### Error 

If a SQL script fails to execute, the application can display the error.

![error](https://github.com/rmgpinto/ssd/blob/master/error%20log.jpg)
