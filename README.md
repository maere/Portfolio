

# Portfolio

Below are links to web apps that I coded using Java and Spring on the backend, and Javascript, HTML and CSS on the front end.  These project represent just a portion of the work I did at the Software Craftsmanship Guild.  Some of the projects below were worked on solo, some were developed with a pairing partner, and the last one was a group effort.  These details are noted below each project link along with a link to the source code.  


----------


  [Multi-Calculator Basic Web App](http://multicalculator-guildwork.rhcloud.com/) 

> This was the first MVC web app I built. I refactored a bunch of calculators that I originally developed as console apps and combined them into a web app with a basic front end.  All work on this project is mine. 
> 
> Here is the [source code](https://bitbucket.org/maere/multicalculatorapp) for the web app.

> (Note: The loan amortization got messed up when I refactored and this needs to be fixed. But here is a [link to the original console app source](https://bitbucket.org/maere/loaninterestcalculator) which actually outputs the correct calculations!)


----------


 [Flooring Master Console App](https://bitbucket.org/maere/flooringmastery) 

> This is a console-based order processing app that persists its data to a text file.  Since this was designed to run in the console, it has no front end currently, but you can view the source code from the link below. 
> 
> This project was done with a pairing partner, and our biggest challenges on this project (as neophyte coders) were:
> 
> -  deciding on the data structures we should use
> - deciding when and where we needed to instantiate our data structures
> - how the classes should relate to each other and how the application should be constructed
> - making sure all of our unit tests passed after each refactoring iteration
> 
> We learned a lot!
> 
> Here is the [code.](https://bitbucket.org/maere/flooringmastery)
> 


----------


 [Address Book App](http://addressbook-guildwork.rhcloud.com/) 

> This is a basic address book application that allows you to add someone's street address and phone number to a live back-end database. Strangely, it has no field for an email address (this was not a requirement). For this reason, my pairing partner and I decided to make it a "vintage" address book.   (Entertaining ourselves with irony.) We used Bootstrap for the layout.
> 
> This app was a really fun one to work on, as my pairing partner was hilarious. So we managed to learn a lot and have fun at the same time. That is actually my ideal work environment. 
> 
> Here is the [code](https://github.com/maere/addressbooklocal) for the project. You can see a palimpsest of sorts in the comments where previous iterations of the code were commented out as the code was refactored from a console app, to a Spring servlet app using JSTL, to an Ajax app (in-memory), to its final database implementation. 
> 
> Note:  Our search implementation uses lambda, and when I went to deploy the app, I found that our search function was unsupported, since lambdas only work in Java 8 and the deployment environment only supported Java 7.  So the search function will need to be refactored to work in this particular deployment environment.


----------


 Basic Content Management System
 
> This application was developed as a group project with three other people. The goal of the project was to enable a small business owner or hobbyist to create their own website/blog without having to write any code.  The site admin would need to be able to create and edit both static web pages and blog posts using a WYSIWYG editor.  
> 
> Planning:
> To prepare for collaborative work on a more complex application we developed planning documents that included a UML diagram, wireframes, and a database schema. We also created user stories in Trello to assist us developing the project in an Agile manner.
> 
> Building:
> We created a multi-tier MVC application with MySQL on the back-end, a DTO package for our models, a DAO package for our interfaces and the DB implementation, and, of course, a package for the controllers.  The app provides basic CRUD functionality using JDBC templates, and either JSTL or AJAX and jQuery to populate the respective page (depending on what was appropriate).  
> 
> Plug-ins:
> The WYSIWYG functionality was created by using the plugin TinyMCE. We also implemented the ability to add and store images into the database via a byte array, and used Spring Security for the admin login.  
> 
> Testing:
> We wrote unit tests for our DAO, and you can test the app as well by signing in as the admin when you get the login prompt:

> user: admin
> password: password
> 
> Project Management:
> The project management on a group project like this was one of the more challenging aspects of the work, since it was a self-managing group and we spent a fair amount of our shared time on communicating, merging, etc. But we got a basic implementation of the project finished, and we will continue to implement the remaining features over time (e.g. the ability to add hashtags, comments, categories, search, etc.).
> 
> Here is [code](https://bitbucket.org/maere/cmssource) as it is in it's current state.


----------


These apps represent some of my initial forays using Java to code  the backend and middle tiers, as well as working in the full stack with Ajax and jQuery.  

After cleaning and tightening up some of the work shown here, I want to start exploring the mobile space. I am enrolled in a workshop on iOS at the end of September, and I plan to start work on a personal project that is a mobile app over the next few months. So stay tuned!

