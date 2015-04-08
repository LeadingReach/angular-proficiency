###LeadingReach Angular Test

To get started:

Clone the Git repository.

LeadingReach uses bower as our JavaScript package manager of choice (it pairs quite well with angular). If you've never used bower before,
see this page for instructions on how to install it. After installing bower, you may continue with the instructions below:

Run `bower install` from your cloned repository to install all vendor files. This will create a "vendor" directory, with all the scripts you should need.

Add the Angular and Restangular scripts to your index.html page to give yourself access to those libraries as injectable services in your AngularJS controllers.

### Test Instructions

For this exercise, you'll be querying a remote API, named [Bloom API](http://bloomapi.com), and displaying the results in a list.

LeadingReach uses Restangular for all of our REST calls, so you'll probably need to view their [docs]() to figure out how their scripts work if you're not familiar with it.

