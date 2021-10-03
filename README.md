# **Family Recipes**
[View a live version of Family Recipes here]()
This is the main website for *Family Recipes*. This website will allow customers to store their precious family recipes, so they are never lost again. 
![Family Recipes on mobile, ipad, ipad pro and desk top.](static/testing/homepage.png) "Family Recipes on multiple displays"

## Table of Contents
### [User Experience](#user-experience-(ux))
### [Project Goals](#project-goals)
#### [User Stories](#user-stories)
* [First Time Visitor Goals](#first-time-visitor-goals)
* [Returning Visitor Goals](#returning-visitor-goals)
* [Frequent Visitor Goals](#frequent-visitor-goals)




### [Design](#design)

* [Color Scheme](#color-scheme)
* [Typography](#typography)
* [Imagery](#imagery)
* [Features](#features)
* [Wireframes](#wireframes)
### [Technologies Used](#technologies-used)
* [Languages Used](#languages-used)
* [Frameworks  Libraries and Programs Used](#frameworks-libraries-and-programs-used)
### [Deployment](#delpoyment)
* [GitHub](#github)
* [Cloning to Local Device](#cloning-of-repository-to-a-local-device)
* [Setting up a google maps javascript API](#Setting-up-a-google-maps-javascript-API)

### [Testing](#testing)
### [User Stories] (#)
[Photo story for first time user](#photo-story-for-first-time-user)
[Bugs](#bugs)
- [Gallery](#gallery)
- [Navbar](#navbar)
- [form](#form)
- [Javascript for Maps](#javascript-for-maps)
- [Javascript for mail](#javascript-for-mail)
### [Acknowledgements](#acknowledgements)
* [Media](#media)
* [Individuals](#individuals)


## User Experience (UX)

### Project Goals 

 * A website that allows user full CRUD(Create, Read/Locate , Update and Delete) functionality. 

 * Site will use HTML, CSS, jQuery, Python, Flask and MongoDB.

 * Website will provide Users the chance to login, create and edit website. 

 * A user friendly website.

 

#### First Time Visitor Goals
 
 1. A first time user will be able to visit the site on any device. 
 
 2. A first time user will register their account.
 
 3. After registering their account the can then add a recipe, edit a recipe and search for recipes using ingredients. 

 #### Returning Visitor Goals

 1. Will be able to login to their account. 

 2. They can also search for new recipes, add new recipes and edit old recipes. 

 #### Frequent Visitor Goals.

 1. Learn new recipes.

 2. Continue to add to their recipe book. 

 3. Double check recipes when making dinner on your mobile. 

# Design 
  ## Color Scheme  
  * Three main colors where chosen. White background, black font like a notebook and teal buttons. 
  
  * Red button for deletion warning.
   
 ## Typography 
    
  * Font used is Pacifico and cursive for logo and Oswald for the main body.  Pacifico font is to conjure the image of a notebook.

 ## Imagery
  * Images used were from Unsplash, BBC Food URLs and the main hero image is from Shutterstock.
  
## Features
* Responsive on all devices. To be able to add recipes to a database that are then shared online. Allowing Icons that link to further social media updates.

## Wireframes

* Wireframe for the whole project. [View](assets/wireframes/tohk2021.pdf)


![Homepage wireframe.](images/tohk2021.png) "Home page wireframe "
"

# Technologies Used 
## Languages Used 
* HTML
* CSS
* Jquery
* Python
## Frameworks Libraries and Programs Used 
1. [Materializecss](https://materializecss.com/)
  
    Materialize CSS

2. [Heroku](https://dashboard.heroku.com/apps)

    Used to deploy app. 

3. [MongoDB](https://account.mongodb.com/account/login?signedOut=true)

    Database usedto store recipes and site info.  

4. [Google Fonts](https://fonts.google.com/specimen/Pacifico?preview.text=Pacifico&preview.text_type=custom&query=Pacifico)

    Pacifico font used.
5. [Fontawesome](https://fontawesome.com/)
    Fontawesome was used for to get icons for utensils and aa cocktail on the feast page. 
6. [Gitpod](https://gitpod.io/workspaces/)
    Used gitpod to work on my repositories. 
7. [Github](https://github.com/MichelleCoffey/A_Moveable_Feast_Shanghai/tree/1a91746d21707106faef91c699500aff9414e097)
     GitHub is hosting my repositories. 
8. JQuery: 
    * Used for materialize

9. [Balsamiq](https://balsamiq.com/)
    * Balsamiq was used to design and organise my WireFrames. 
10. [TinyPNG](https://tinypng.com/)
     * Tinypng for fomatting images, so they loaded faster.
11. [Unsplash](https://unsplash.com/)
    * Upsplash was used to access some stock images to add to the site and in particular the hero image and background image. 
12. [Shutterstock](https://www.shutterstock.com/)
    * Shutterstock was used for the heroimage. 
13. [BBC FOOD](https://www.bbc.co.uk/food)
    * Recipes.

14. [Werkzeug](https://werkzeug.palletsprojects.com/en/2.0.x/)

    Used for security and passwords. 

15. [RandomKeyGen](https://randomkeygen.com/)


## Deployment 
### Github

### Requirements 
  1. Github account
  2. Gitpod account
  3. Mongo db account
  4. Flask 
  5. heroku account


#### The repository is hosted on github and I have therefore used github pages to deploy the site. 
  1. On Github, go to your site's repository.
  2. Under your repository name, click settings and scroll down to Github pages. 
  3. Under the "Github pages:", use the None or Branch drop-down menu and select a publishing source. For a Moveable Feast, the master was selected, root and both actions were saved using the save button. A theme or custom domain were not chosen at this time. 
  4. After saving the actions. Next click the active link on the repository page on Github. Full deployment may take a minute or two, so refresh the page and be patient. 
  
#### Cloning of Repository to a local device.
  1. On GitHub, again go to the main page of the repository. 
  2. Above the ist of files, click Code. 
  3. To clone the repository using HTTPS, under "Clone with HTTPS", click. 
     To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click Use SSH, then click . 
     To clone a repository using GitHub CLI, click Use GitHub CLI, then click .
  4. Open Terminal 
  5. Change the current working directory to the location where you want the cloned directory. 
  6. TYpe git clone, and then paste the URL you copied eariler. 
  7. Press Enter to create your local clone. 

#### Working with Gitpod
  1. Install all of the requirements. In the termianl window type pip3 install -r requirements.txt.
  2. Create a databae in Mongo db. 
      * Sign up if needed. 
      * Create and cluster and a database. 
      * Create cluster for family_recipes and in it create a further three collections: user, categories, and recipes. Add string values. 
  3. Create the variables. 
    * Create a gitignore file and create and env.py file. 
    * Add environment variables. 

                  Import os
              os.environ.setdefault("IP", "Added by developer")
              os.environ.setdefault("PORT", "Added by developer")
              os.environ.setdefault("SECRET_KEY", "Added by developer")
              os.environ.setdefault("MONGO_URI", "Added by developer")
              os.environ.setdefault("MONGO_DBNAME", "Added by developer")
          
    #### Heroku Deployment

    1. In terminal window type pip3 freeze -- local > requirements.txt.
       * Then write python app.py > Procfile. This file is needed by Heroku. 
    2. Create a Heroku account. 
    3. Choose deployment method via Github. Search your github using the name of your repository name. 
       *  Click on the repository to connect with it. 
       * Add Config Vars in settings. 
       * ENTER IP, PORT, SECRET_KEY, MONGO_URI, MONGO_DBNAME.
    4. Push requirements.txt and Profile from gitpod. 
    5. Use Automatic Deployment on Heroku and Deploy Branch

                            
## Testing 

### Photo story for first time user

### User Stories

 ![Family Recipes homepage on mobile, ipad, ipad pro and desk top.](static/testing/homepage.png) "Family Recipes on multiple displays."


W3C CSS Validator Services was used to validate CSS.

![successful validation confirmation](static/testing/csstest.png) "CSS Validation."
 * This was successful.

 ![successful validation confirmation](static/testing/pep8.png) "Home Page HTML success."
 * This was successful but there was white space on blank like that would not change.

![successful validation confirmation](static/images/mapjsval.png) "Home Page HTML success."

![successful validation confirmation](static/images/mailjsval.png) "Home Page HTML success."

![Lighthouse Performance 77%, Accessibilty 89%, Best Practices 93%, SEO 100% on desktop](static/testing/lighthouse.png) "Lighthouse score for the websites user efficency."

### Bugs
#### Mongodb

1. The trickiest part is connecting mongodb and to gitpod. The main issue is knowing where to add the name and password to your MONGO_URL. This seemed to have a delayed response for me as it did not initial work but worked the following morning. I use a VPN in China and can cause some glitches. First test didn't work because I had missed a closing " in my html. Once rectified it all worked and stored info in the databases.

#### Images and form
* After adding a flex component to css this cause my images to distort. I removed the flex to specific areas instead. 

 #### Form 
 * The form pushed left on small devices. I removed the width of 400px, which helped and then targeted the media query on larger devices. 

 #### Home Page
 * I had a link to the recipes which allowed the user to bypass login and register. I removed this from the site. 


## Acknowledgements
### Media
* Code Institute Tutorials for providing a jumping off block. 
 * Slack for being a great source of help with either googling or when other students have provided suggestions to help improve your work. 
 * Code Institute Tutorials. 

 ### Individuals
 * My Mentor, Precious Ijege. 
 * Tutors at Code Institute are great guiding hand.   They do not give you the answer but ask the right questions to lead you down the correct path. It also helps build confidence. 
 * Anne Greaves and Code Institute for a comprehensive guide to writing README.md. The template was taken from the Code Institute Guide to writing README and how to write Markdown.

 * Juan Stelling - breaktasty for a thorough README. I used elements of his and Anne Greaves README. 

 * Alex Harvey, a guide to writing a table of contents in gitpod. 


#### Code
  

 [Tim Nelson Task Manager](https://github.com/Code-Institute-Solutions/TaskManagerAuth)

 * This was used as the template for creating and connectimg my own python, mongodb database. 

 * Peer Code for ideas and examples implementation.

 * Lazy Vegan for how to deal with images in the database by  Jenny Malone.

 * Juan Stelling for breaktasty for examples of README. 

 ### Credits 

 * BBC Food for all food pic URLS and recipes.

 * Shutterstock for land page hero image by Iryn.

 
 