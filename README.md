# Tech Blog
## Bootcamp Challenge 14: Model-View-Controller (MVC)
[![MSU](https://img.shields.io/badge/MSU-Coding%20Bootcamp-green/)](https://bootcamp.msu.edu/)

## Technologies
![Technologies](https://img.shields.io/badge/-Git-F05032?logo=Git&logoColor=white)
![Technologies](https://img.shields.io/badge/-JavaScript-007396?logo=JavaScript&logoColor=white)
![Technologies](https://img.shields.io/badge/-Node.js-339933?logo=Node.js&logoColor=white)
![Technologies](https://img.shields.io/badge/-npm-CB3837?logo=npm&logoColor=white)
![Technologies](https://img.shields.io/badge/-MySQL-4479A1?logo=MySQL&logoColor=white)
![Technologies](https://img.shields.io/badge/-Sequelize-52B0E7?logo=Sequelize&logoColor=white)
![Technologies](https://img.shields.io/badge/-Express-000000?logo=&logoColor=white)
![Technologies](https://img.shields.io/badge/-dotenv-000000?logo=&logoColor=white)
![Technologies](https://img.shields.io/badge/Heroku-430098?logo=Git&logoColor=white)

## Description
Writing about tech can be just as important as making it. Developers spend plenty of time creating new applications and debugging existing codebases, but most developers also spend at least some of their time reading and writing about technical concepts, recent advancements, and new technologies.

This is a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developersâ€™ posts as well. The app follows the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.

## Instructions
<b>User Story:</b><br />
```
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```

<b>Acceptance Criteria:</b><br />
```
GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creatorâ€™s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creatorâ€™s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the site for more than a set time
THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments
```
## Mock-Up
The following animation demonstrates the application functionality:
![14-mvc-homework-demo-01](https://user-images.githubusercontent.com/98504854/169637063-776f5c31-351b-4389-84dd-f5e4cc5fc0b7.gif)

## Link
A link to the [code](https://github.com/moyangdev/tech-blog):
```
https://github.com/moyangdev/tech-blog
```
A link to the deployed [application](https://tranquil-meadow-73235.herokuapp.com/):
```
https://tranquil-meadow-73235.herokuapp.com/
```
