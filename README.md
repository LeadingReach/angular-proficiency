###LeadingReach Angular Test

To get started:

Clone the Git repository.

LeadingReach uses bower as our JavaScript package manager of choice (it pairs quite well with angular). If you've never used bower before,
see [this page](http://bower.io/#install-bower) for instructions on how to install it. After installing bower, you may continue with the instructions below:

Run `bower install` from your cloned repository to install all vendor files. This will create a "vendor" directory, with all the scripts you should
need.

Add the Angular and Restangular scripts to your index.html page to give yourself access to those libraries as injectable services in your AngularJS
controllers. We've also included Twitter Bootstrap (our CSS library of choice) in the vendor directory if you'd like to make your page look nicer.

### Test Instructions

For this exercise, you'll be querying [Bloom API](http://bloomapi.com) (an API that uses the NPI database to find physician/provider data), and displaying the results in a list.

LeadingReach uses Restangular for all of our REST calls, so you'll probably need to view their [docs](https://github.com/mgonto/restangular)
to figure out how their scripts work if you're not familiar with it.

####Requirements

1. In your index.html page, you'll find two input fields. Use these to collect First Name and Last Name.
2. Add a button to the index page that submits a query to Bloom API with the information currently in the First and Last Name fields.
3. Write an AngularJS controller (in angular-proficiency.js, but you may use more files if you need) to handle querying the API.
   - If you're feeling up to it and want some bonus points, create a directive to replace the "Search" button that runs the search when clicked.
4. Write markup in index.html to display the list of results retrieved from the Bloom API. This doesn't have to look perfect, but please don't just
dump the response JSON into the page. For example, take the array of results and create a list that displays First Name, Last Name,
and some basic contact information.


####Submission
When you've finished your application, please delete the vendor directory and zip up the rest of the contents into a .zip file and email it to
dev@leadingreach.com