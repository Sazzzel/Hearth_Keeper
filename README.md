# Hearth Keeper

![Hearth Keeper responsive screenshot ADD THIS]()

## Introduction

Hearth Keeper is a recipe website that has been created to what I would like to see in a resipe site. I think a recipe site should be somewhere not only to share your recipes but also to share experiences on cooking others resipes and how they adapted it to their liking. Hearth Keeper has been developed as part of the Code Institute's Full-Stack Developer course as my final project - focusing on Django and Bootstrap frameworks, Database manipulation and CRUD functionality.

View live site here : [Hearth Keeper ADD THIS]()  
  
For Admin access with relevant sign-in information: [Hearth Keeper Admin ADD This]()

<hr>

## Table of Contents

- [Hearth Keeper](#Hearth-Keeper)
  - [Introduction](#introduction)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
- [UX - User Experience](#ux---user-experience)
  - [Design Inspiration](#design-inspiration)
    - [Colour Scheme](#colour-scheme)
    - [Font](#font)
- [Project Planning](#project-planning)
  - [Strategy Plane](#strategy-plane)
    - [Site Goals](#site-goals)
  - [Agile Methodologies - Project Management](#agile-methodologies---project-management)
    - [MoSCoW Prioritization](#moscow-prioritization)
    - [Sprints](#sprints)
  - [User Stories](#user-stories)
    - [Visitor User Stories](#visitor-user-stories)
    - [Epic - User Profile](#epic---user-profile)
    - [Epic - Articles](#epic---articles)
    - [Epic - Booking](#epic---booking)
    - [Epic - Photo Gallery](#epic---photo-gallery)
    - [Epic - Visit Us/Reviews](#epic---visit-usreviews)
  - [Scope Plane](#scope-plane)
  - [Structural Plane](#structural-plane)
  - [Skeleton \& Surface Planes](#skeleton--surface-planes)
    - [Wireframes](#wireframes)
    - [Database Schema - Entity Relationship Diagram](#database-schema---entity-relationship-diagram)
    - [Security](#security)
- [Features](#features)
  - [User View - Registered/Unregistered](#user-view---registeredunregistered)
  - [CRUD Functionality](#crud-functionality)
  - [Feature Showcase](#feature-showcase)
  - [Future Features](#future-features)
- [Technologies \& Languages Used](#technologies--languages-used)
  - [Libraries \& Frameworks](#libraries--frameworks)
  - [Tools \& Programs](#tools--programs)
- [Testing](#testing)
- [Deployment](#deployment)
  - [Connecting to GitHub](#connecting-to-github)
  - [Django Project Setup](#django-project-setup)
  - [Cloudinary API](#cloudinary-api)
  - [Elephant SQL](#elephant-sql)
  - [Heroku deployment](#heroku-deployment)
  - [Clone project](#clone-project)
  - [Fork Project](#fork-project)
- [Credits](#credits)
  - [Code](#code)
  - [Media](#media)
    - [Additional reading/tutorials/books/blogs](#additional-readingtutorialsbooksblogs)
  - [Acknowledgements](#acknowledgements)

  ## Overview

Hearth Keeper is an recipe website to save your recipes and more. Users are invited to:

- Join the Hearth Keeper community
- Upload their own recipes.
- Rate recipes.
- Comment on recipes.
- Change grams to cups with ease.
- Alter the recipe depending how many people it should serve.
- Add their favourite recipes to their Cookbook
- Try the BETA version to upload recipes from a cookbook by image.

Hearth Keeper is accessible via all browsers and is full responsiveness to fit different screen sizes. Its aim is to create a community for people who love to cook and who want to try new and exciting recipes. 
I wanted to create a site that is built for a community and not just to lookup recipes. A site where people can comunicate via the comments, added suggestion or suggest how this can be prepared for people with certain allergys or preferences. I created this site as I love to cook and following recipes can be hard when you have to convert them from cups to grams and vice versa. I also have noticed that many recipes are made to serve 2 - 4 people, people who live alone or have bigger familes my stay away from these recipes due to the size and not wanting to waste ingredients on attepting to reduce or expand the recipe to suit their needs. I have made this site so it will do these calculations for you so a recipe will be available to anyone without worry. 
I hope to offer users their own profile pages where they can set their favourite recipes with links. 

# UX - User Experience

## Design Inspiration

I was really excited to get working on this project as it is something that I wished all recipe sites had. I wanted to create a website that anyone can use, for people who are neuro-spicy (neurodiverse) I want to keep the website clean, open and straight to the point. A few webistes I have seen go into so much detail about how the recipe came to be and about the site it's self. This is when the recipe gets lost in a forrest of paragraphs. The sites are full of useful information but I feel the extra information should be linked to the page rather than being forced on the user. This is one of the main reason I wanted to create this website. I also want to make it easier for the user to change the recipes from cups to grams and vice versa. I also wanted to take the hassle out of changing a recipe for more or less servings, letting the website calculate this for you.
For my colours I used ChatGPT to create a logo that I liked. I am using the colours from the logo and other that completemnt . For my   Once I had chosen the font of 'Outfit' and created the logo on Procreate, the website content followed swiftly and I had great fun developing it.

![Hearth Keeper logo](documentation/final_views/logo.png)  
*Hearth Keeper logo* 

### Colour Scheme

As mentioned above, the main colours I used in my colour scheme came from the logo that I made using ChatGPT. I wanted to create a welcoming and easy to use environment for the user. The colours stay mainly the same through out the website, this is to provide the users with an easy to use website and allow neuro-spicy (neurodiverse) people to feel safe while using the site. I wanted to go with an almost antique feel.

The corresponding sections and colours and identifying CSS variables are:

-
-

![balancing colours for website text,background and Login/Logout icon ADD THIS]()  
*Black, white and grey used for backgrounds, text and Login/Logout icon*

![screenshot of colour scheme ADD THIS]()  
*Colour Scheme for Hearth Keeper website*

![colour blind safe colour swatch ADD THIS]()  
*Accessibility check for colour scheme*

### Font

Using [Google Fonts](https://fonts.google.com/), I imported 'this ' and 'that' as a complementary font to my CSS file. 

In development, 'this' was used as my main font for all titles, whilst 'That' was set as my main font for the rest of the site.

# Project Planning  
 
## Strategy Plane

My project goal was to build a simple recipe website with additional features that I feel in this day and age are nessasery. The main goal was to allow users to add and edit their recipes and comments on the site while also allowing them to also delete any unwanted recipes or comments they created. To bring the site into the 21st centurany I wanted to allow users to change the weight metrics to allow anyone in the world to make the recipe. Also allowing the user to change how many people the recipe should cater for, then updating the recipe using this information.  

### Site Goals

- Create a safe and wlcoming environment for people who love to cook.
- Create an easy to use and wlcoming environment for people who want to try new recipes.
- Make it an easy expeiance to convert weight metric for all recipes.
- Let users to set how many servings they need and the recipe to update.
- Allow users to add recipes and comments to the site.
- Users have their own cookbooks to store their favourite recipes.
- UX will remain the same on all devices.
- Addition of future features to help grow the website into a comunity.

## Agile Methodologies - Project Management

Before starting work on Hearth Keeper I used my [Github Projects Board ADD THIS]() to plan and document all of my work.

### MoSCoW Prioritization

I chose to follow the MoSCoW Prioritization method for Hearth Keeper, identifying and labelling my:

- **Must Haves**: the 'required', critical components of the project. Completing my 'Must Haves' helped me to reach the MVP (Minimum Viable Product) for this project early.
  
- **Should Haves**: the components that are valuable to the project but not absolutely 'vital' at the MVP stage. The 'Must Haves' must receive priority over the 'Should Haves'.

- **Could Haves**: these are the features that are a 'bonus' to the project, it would be nice to have them in this phase, but only if the most important issues have been completed first and time allows.

- **Won't Haves**: the features or components that either no longer fit the project's brief or are of very low priority for this release. Also I will use this tags for any future features I wish to add to my project at a later date.

### Sprints

I broke my process into User Stories and Testing Tasks, which I converted into issues and labelled fully on my projects board. [Github Projects Board ADD THIS]()

## User Stories

All of my user stories can be seen on my [Github Projects Board ADD THIS](). They were all made before I started my project and managed throughout the development. 

## Scope Plane

As this would not only be the building of my final project but also a learning experiance using new API's and covering many to many databases. I have built this website using technologies I didn't know exsisted before I started this 16 week Full Stack Course. These technologies include Django, Bootstrap and Cloudinary. I follwed my agile planning and my user stories to help me keep on track and not fall into the many "what if I add..." sinarions. I did however write these down on paper with the forsite of adding these as my future fatures. I added my User Stories and Testing Tasks as issues on my [Github Projects Board ADD THIS]().

Essential features of my project were:

- A Responsive website for all device sizes 
- User Authentication
- Recipe feature with full CRUD functionality
- Comments feature with full CRUD functionality

I planned my project thoroughly as this has been something I have wanted to use for a long time. No other site I have used previously have lived upto my expectations of what a recipe site in 2024 should offer. 

## Structural Plane

![navbar icons ADD THIS]()  
*Navigation icons for Hearth Keeper*  

![header ADD THIS]()  
*Sign Up page header*  

## Skeleton & Surface Planes

### Wireframes

The wireframes for Hearth Keeper were created in Figma. [Figma](www.figma.com) is an easy and fast design system that is a cloud-based design tool. It is easy to make user interface (UI) and user experience (UX) design projects. It’s a vector graphics editor that allows designers and developers to create, prototype, and test digital products such as websites, mobile apps, and software interfaces.

**Mobile/Tablet view for:**  

- Home
- Recipes
- My Cookbook

I wanted an easy to use website, that has a welcoming feel to all users.

<details open>
    <summary>Mobile/Tablet Home Page Wireframe</summary>  
    <img src="">  
</details>

<details>
    <summary>Mobile/Tablet Recipes Page Wireframe</summary>  
    <img src="">
</details>

<details>
    <summary>Mobile/Tablet Recipe Page Wireframe</summary>  
    <img src="">
</details>

<details>
    <summary>Mobile/Tablet My Cookbook Page Wireframe</summary>  
    <img src="">
</details>

**Desktop view for:**

- Home
- Recipes
- My Cookbook

<details open>
    <summary>Desktop Home Page Wireframe</summary>  
    <img src="">  
</details>

<details>
    <summary>Desktop Recipe Page Wireframe</summary>  
    <img src="">
</details>

<details>
    <summary>Desktop Recipes Page Wireframe</summary>  
    <img src="">
</details>

<details>
    <summary>Desktop My Cookbook Page Wireframe</summary>  
    <img src="">
</details>


### Database Schema - Entity Relationship Diagram

![ERD Image]()  
*Database Schema (ERD) for Hearth Keeper displaying relationships between components within the database*

The Entity Relationship Diagram (ERD) illustrates how various features interact with each other and connect to the PostgreSQL database. The system uses Django's built-in User model and Django AllAuth for user authentication. Upon registration, a user_id is created for each user, based on their username and email. This allows the user to create a profile, which is used to log into the site. Users can then create new recipes, upload photos, add comments to recipes, rate them, and manage their personal "My Cookbook," which contains their favourite recipes.

The Comments Model were inspired by the blog walkthrough by the Code Institute. This takes the username of the user via the user_Id as a forigenkey and lets them leave a comment on a recipe via the recipe_id that will require the admin to review and approve. 

Recipes Model collects data from the user. The title, ingredience and method and the serving amount. This takes the username of the user via the user_Id as a forigenkey

Through the Admin Django Dashboard the super user will have access to approve or delete recipes and comments from all users. The super user can also delete the the user and all the data that user has added to the site.

### Security


Several security measures were implemented in this project to safeguard user-submitted data. Unlike a purely informational website, Hearth keeper enables users to engage with the community. To comply with stringent internet security standards and ensure the protection of user data, the following processes were incorporated into the development of the project.

**AllAuth**  

Django AllAuth is an installable framework that handles user registration and authentication. Authentication was essential for determining whether a user was registered or unregistered, as well as controlling access to content on Hearth Keeper. The setup of AllAuth involved the following steps:

- Installing it as a dependency in my workspace
- Adding it to the INSTALLED_APPS section of settings.py
- Configuring the AUTHENTICATION_BACKENDS in settings.py using the settings from the AllAuth documentation
- Including its URL in the project's urls.py
- Running database migrations to create the necessary tables for AllAuth
- (For this version of Hearth Keeper the email and social account sign-ups were not enabled. This was to make sure my website met the MVP. These features will be added in the next release.)
  
**Defensive Design**  

Hearth Keeper was built using my current knowledge of Django and focused on providing a smooth user experience.

- Input validation and error messages give users helpful feedback, guiding them toward their intended actions.
- Unregistered users are redirected to the Sign-Up page when attempting to access restricted areas.
- Authentication controls ensure that edit and delete icons are visible only to the content’s author.
- Data deletions are confirmed with an additional modal, prompting the user to verify their decision.
- Error pages include a "Take me home" button to help users easily return to the main page.
- Thorough testing and validation ensure the features work as expected.

**CSRF Tokens** 

CSRF (Cross-Site Request Forgery) tokens are included in every form to authenticate the request with the server upon submission. Without these tokens, a site becomes vulnerable to attacks where malicious actors could steal user data.
  