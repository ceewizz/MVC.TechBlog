# MVC.TechBlog
Module 14 Module View Controller: Tech Blog

## User Story
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions

## Acceptance Criteria
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
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
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
THEN I am able to view posts and comments but I am prompted to log in again before I can add, update, or delet

## Descriptions
This full-stack application allows users to create and interact with tech industry content. Using the dashboard page, users can upload content, comment on other users' posts, edit and delete their own posts. On the homepage, users can view all current posts without creating an account, but they will need to login or create an account when they try to access the dashboard, or create or view specific posts. User authentication via session storage and cookies is utilized in the application and offers a secure profile through specific routing and page protection. Users' passwords are hashed through the bcrypt dependency before being entered into the MySQL database giving additional safeguards to users.

## Technologies-Used
Sequelize
Nodenon
Node.js
Bootstrap
Express.js
Javascript
Mysql
Npm
Jest
Insomnia

## Instructions
1. Clone repo, Open in VS Code
2. Install node.js, then do npm init -y
3. Then do npm i 
4. Then install all the dependencies using the following command
npm i sequelize
npm i mysql2
npm i express@4.18.2
npm i doteenv
npm i nodemon
npm i bcrypt
npm i bootstrap
npm i connect-session-sequelize
npm i express-handlebars
npm i express-session
npm i jest
5. then will need to make sure you have an added .env file within the root directory of your repository variables specifying the database name, your MySQL username, and your MySQL password. This will need to be completed before running the application, and will allow the connection.js file to utilize your environmental variables keeping your sensitive information protected.
6. Then do mysql -u root -p then enter your mysql password
7. Then run the schema.sql file which will create a database
8. Once database is created, you will need to seed
9. Then run the db from root directory using npm start
10. With nodemon installed use the command npm run to start up server
11. Then with Insomnia you can test the functions of routes in the program and make changes to both the back and front end of the code.


## Links
Github Repo : https://github.com/ceewizz/MVC.TechBlog
Deployed Links: 