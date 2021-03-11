# README

API Object Models To Generate:

* Blogs = g resource Blog blog_name:string b_description:text
* Projects = g resource Project project_name:string p_description:text demo_key:string
* Contacts = g resource Contact first_name:string last_name:string email:string description:text

Should I create a blogs model?
It might be best to fetch my blogs from Medium on the front end using their API or scraping my homepage...

Projects Model would make it easier for me to add projects, however I should have an Admin to go with it that way I am the only person who can do this, consider implementing an admin login to add projects?

Contacts Model is the primary reason for this API, I need a way to store the data from the contact form and utilize it, I could render it via an admin login page or send all the contact form data to a spreadsheet.


-------------


This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
