A)
 1) what are I building? - personal site a place to blog, share my work and have people contact me
	2) Who am I  building it for?  I am  building it for myself but also for the community as a whole. Sharing what I am learning by blogging.
	3) What features do we want to have- 
           a) create / edit / destroy 
           b) markdown 
           c) syntax highlighting
          d) comments (Disqus) 
    - projects
           a) Create edit destroy
     -contact 
           a) contact form 
           b) sendgrid  // sends emails in app
    -User (devise)


	B) User stories- 
	1) "As a black I want to be able to blank so that blank"
	2) As a user I want to be able to create posts so that I can share what I am learning on my blog
	3) As a user I want to be able to edit and destroy posts so that I can manage my blog
	4) As a user I want to be able to write posts in markdown so that it is eaiser for me to write posts
	5) As a user I want to be able to highlight the various syntax of code blocks that I share on my blog
	6) As a user I want to shoe the visitors and potential employers example of my work or stuff I have build
	7) As a user I want to be able to have visitors contact me thorough a form on my site 
	8) As a sure I want visitors to be able to leave comments on my posts



Model our data
  Posts
	Title: string
	Content:text
	
Project
	Title:string
	Description:text
	Link:string
	
User
	Devise
	
	
Thinking through the pages of app

	1) Home
	2) Posts#index
	3) Posts#shoe
	4) Projects#show
	5) Contact

