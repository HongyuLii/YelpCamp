#YelpCamp

* ADD Landing Page
* Add Campgrounds Page that lists all campgrounds

Each Campground has:

* Name
* Image

[
{name:"Salcom Creek", image: ""}
]

#Layout and Basic Styling
*header and footer
*Bootstrap

#create new campgrounds
*setup new campground post routes
*add in body parser
*Setup route to show form 

#Style the campground page

#Show Page
* Review the RESTful routes we've seen so far
* Add description to our campground model
* Show db.collection.drop()
* Add a shwo route/template

#Refactor Mongoose Code
* Create a models directory
* Use module.exports
* Require everything correctly!

#Add Seeds File
* Add a seeds.js file
* Run the seeds file every time the server starts

#Add the Comment model!
* Make out errors go away!
* Display comments on campground show page

#Comment New/Create
* Discuss nested routes
* Add the comment new and create routes
* Add the new commnet form

#Style Show Page
* Add sidebar to show page
* Display comments nicely

##Add User Model
* Install all packages 
* User Model

##Authn Pt.2 -register
* Configuration Passport
* Add register routes
* Add register template

##Auth Pt.3 -Login
* Add login routes
* Add login template

##Auth Pt.4 -Logout/Navbar
* Add logout route
* Prevent user from adding a comment if not signed in
* Add links to navbar
* Show/hide auth links correctly

##Refactor The Routes
* Use Express routes to reoragnize all routes

##Users + Comments
started with editing comment model by adding author object
comments route, 
display comment.author.name

##Users + Campgrounds
* Prevent an unaithenticated user from creating a campground
* Save username + id to newly created campground

#Editing Campgrounds
* Add Method-Override
* Add Edit Route for campgrounds
* Add link to Edit Page
* Add Update Route
* Fix set problem 

#Deleting Campground
* Add Destroy Route
* Add Delete button

#Authorization
* User can only edit his/her campgrounds
* User can only delete his/her campgrounds
* Hide/Show edit and delete buttons

#Editing Comments
* Add Edit route for comments
* Add Edit button
* Add Update route

/campgrounds/:id/edit
/campgrounds/:id/comments/:id/edit

#Deleting Comments
* Add Destroy route
* Add Delete button

#Authorization Part 2: Comments
* User can only edit their comments etc...
* User can only delete his/her comment

#Flash
* Demo working version
* Install and configure connect-falsh
* Add bootstrap alerts to header