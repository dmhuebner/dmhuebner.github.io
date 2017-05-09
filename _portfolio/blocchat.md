---
layout: post
title: Bloc Chat
feature-img: "img/work_assets/bloc_chat/bloc_chat_thumbnail.png"
thumbnail-path: "img/work_assets/bloc_chat/bloc_chat_thumbnail.png"
short-description: Bloc Chat is an instant messaging app


---
#### **SUMMARY**

Bloc Chat is a simple instant messaging application including user signup and authentication built with *Angular.js* and *Firebase*. It uses the Firebase *AngularFire* module to provide a real-time backend with three-way data binding.

{:.center}
![]({{ site.baseurl }}/img/work_assets/bloc_chat/bloc_chat_thumbnail.png)

#### **EXPLANATION**

The goal of this project was to create a simple instant messaging application with JavaScript and Angular.js that features two way binding and real-time application updates without refreshing the page. It was created according to user stories provided in the Bloc *Full Stack Developer* curriculum. This is a simple but effective instant messaging application that can be expanded on and customized to create more robust chat applications. This project was created to practice and demonstrate my *HTML*, *CSS*, *JavaScript*, and *Angular.js* experience as well as to gain more experience implementing a real-time backend with *Firebase*. For this project, I used the Firebase *AngularFire* module to create a three-way data binding between the HTML, JavaScript and Firebase database. This allows the application to show updates in real time without requiring the page to be refreshed as users write new instant messages. Bloc Chat has a simple, mobile responsive design and utilizes *UI Bootstrap*'s Modal service to require users to signup for a new account or login with an existing email password pair before proceeding to select a chat room.

#### **PAGES**

##### **Login/SignUp Modals:**

Posting instant messages in any room requires a user to be logged in. Users who are not already logged in to Bloc Chat are initially presented with the Login Modal. The Login Modal allows a user to enter an email and password pair to login or they can click "Sign Up" to open the SignUp modal. A cookie is placed on the users browser upon logging in to the website to remember login credentials.

{:.center}
![]({{ site.baseurl }}/img/work_assets/bloc_chat/bloc_chat_login_modal.png)

The Sign Up modal gathers a new user's username, email, and password and uses AngularFire's Authentication API to save them to the database. I created a user object in Firebase to associate the username with the correct Firebase user id. When a user logs into the Bloc Chat the username that is associated with their user id is populated in the top right and is displayed next to any messages they send. Both the Login and SignUp modal utilize *UI Bootstrap*'s Modal service ($uibModal).

{:.center}
![]({{ site.baseurl }}/img/work_assets/bloc_chat/bloc_chat_signup_modal.png)

Once a user is logged in, they can logout by clicking the "Logout" button in the top right. Logging out ends the user session and removes the login cookie from the user's browser.

##### **New Room Modal:**

Once a user logs into the application they will be able to choose a Room from the selection on the left. Additionally, they would be able to create new rooms by clicking the (you guessed it) "New Room" button. The New Room button triggers the New Room modal which also utilizes *UI Bootstrap*'s Modal service ($uibModal).

{:.center}
![]({{ site.baseurl }}/img/work_assets/bloc_chat/bloc_chat_new_room_modal.png)

Currently, there are no authorization restrictions for users on Bloc Chat. Right now any user can create a new room and any other user can access it and write messages in that room. However, user authorization and private room functionality can and will likely be added in the future.

##### **Mobile Responsive Design:**

This application was created with a mobile-first, responsive design using *Bootstrap*.

{:.center}
![]({{ site.baseurl }}/img/work_assets/bloc_chat/bloc_chat_mobile_view.png)

#### **SOLUTION**

The initial approach for this project was to code all of the music player functionality in pure, vanila JavaScript. Once all of the features and application logic were completed, I refactored the code to implement the jQuery library wherever applicable. Once all of the necessary features were finished and fully functional, I refactored the application again to implement the Angular.js JavaScript framework. As a result, the app was resructured from a static website into a Single Page Application (SPA). I used the <a href="https://ui-router.github.io/ng1/" target="_blank">UI Router</a> Angular.js plugin to take advantage of the useful "sref" attribute directive as well as a few other useful features.

The goal was to practice utilizing several different strategies for creating the necessary functionality for the application. I started with the most straight forward stratey, to build the features with pure JavaScript. Then, I refactored the application using the jQuery library to reduce the amount of code needed and to practice refactoring vanilla JavaScript into the jQuery equivolent wherever possible. I then refactored and restructured the app to use the Angular.js framework.

#### **TECHNOLOGIES USED**

HTML5, CSS3, JavaScript, jQuery, Angular.js, Grunt, Git

#### **CONCLUSION**

While the process of initally coding everything in pure, vanilla Javascript and then refactoring it into the jQuery equivolent was certainly more time consuiming than using jQuery to begin with, it was highly beneficial and educational. It empowered me as a developer to feel confident in my JavaScript skills while not feeling like I need to lean on the jQuery library.

The next steps for this project may be to implement a User Login portal so that users are able to sign up and login to use the application. In order to prepare this app for real use, the next step is to write the necessary server side code to enable a user to actually store their own album content in the application's server as well as create and store user login credentials.

#### View the Project:

**<a href="http://blocjamsapp.netlify.com/" target="_blank">BlocJams</a>**

**<a href="http://blocjams-angular.netlify.com/" target="_blank">BlocJams - Refactored with Angular.js</a>**
