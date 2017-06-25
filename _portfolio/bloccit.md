---
layout: post
title: Bloccit
feature-img: "img/work_assets/bloccit/bloccit-header5.png/"
thumbnail-path: "img/work_assets/bloccit/bloccit-thumbnail.png"
short-description: Bloccit - Post, share, comment and vote!


---
**<a href="https://blocchat.netlify.com/" target="_blank" style="font-size: 2rem;">Bloccit</a>**

#### **SUMMARY**

Bloccit is a Reddit-like application designed to let users share and explore posts and links from across the internet. Users can comment on public posts, use **Markdown** to style their own posts and up-vote or down-vote any posts they come across. Bloccit was built with *Ruby on Rails*.

{:.center}
![]({{ site.baseurl }}/img/work_assets/bloccit/bloccit-thumbnail.png)

#### **EXPLANATION**

The goal of this project was to build an application modeled after <a href="http://reddit.com" target="_blank">Reddit</a> to practice building CRUD applications with *Ruby on Rails*. It was created according to user stories provided in the <a href="http://bloc.io" target="_blank">Bloc</a> *Full Stack Developer* curriculum.

Bloccit features custom user authentication and authorization using the *bcrypt* gem and uses Rails' ActiveRecord::Enum class for different user types (admin, moderator, standard, etc.) Guest users can read through posts in public topics and view user comments. User's can create a free account to create their own posts, comment on other users' posts and up or down vote posts they find interesting.

Bloccit has a simple, modern, mobile responsive design optimized for users on any size devise.

#### **PAGES**

##### **Sign Up View:**

Users can either sign up to create a new free account to start posting and exploring Bloccit or sign in with their existing account.

{:.center}
![]({{ site.baseurl }}/img/work_assets/bloccit/bloccit-signup.png)

##### **Sign In View:**

{:.center}
![]({{ site.baseurl }}/img/work_assets/bloccit/bloccit-signin.png)

Once a user is logged in they will be directed to the Topics index view where they can choose a topic, they can logout by clicking the "Logout" button in the top right. Logging out destroys the user session.

##### **Topics index:**

Once a user logs into the application they will be able to create new posts choose a Room from the selection on the left. Additionally, they would be able to create new rooms by clicking the (you guessed it) "New Room" button. The New Room button triggers the New Room modal which also utilizes *UI Bootstrap*'s Modal service ($uibModal).

{:.center}
![]({{ site.baseurl }}/img/work_assets/bloc_chat/bloc_chat_new_room_modal2.png)

Currently, there are no authorization restrictions for users on Bloc Chat. Any user can create a new room and any other user can access it and write messages in that room. However, advanced user authorization and private room functionality can and will likely be added in the future.

##### **Mobile Responsive Design:**

This application was created with a mobile-first, responsive design using *Bootstrap*.

{:.center}
![]({{ site.baseurl }}/img/work_assets/bloc_chat/bloc_chat_mobile_view2.png)

#### **SOLUTION**

Because this is an instant messaging application, it was imperative to write the app in a way that allowed asynchronous updates as users write new instant messages. Angular.js in combination with Firebase and AngularFire were an appropriate approach to achieving the three-way data binding functionality that any good instant messaging app should have.

Bloc Chat was designed and structured as a Single Page Application (SPA). I used the <a href="https://ui-router.github.io/ng1/" target="_blank">UI Router</a> Angular.js plugin to take advantage of the useful "sref" attribute directive as well as a few other useful features that it provides. I implemented the *ngCookies* module to keep track of user sessions as well as *UI Bootstrap* for certain UI components such as the login, signup and new room modals.

I created custom Angular Services and corresponding Controllers to handle the creation of new rooms and new messages. I implemented AngularFire's Authentication API in conjunction with a custom Account service to correlate AngularFire user IDs with usernames stored in the Firebase database. I used the AngularFire module to read and write records to the Firebase database asynchronously.


#### **TECHNOLOGIES USED**

HTML5, CSS3, JavaScript, Ruby on Rails, Git

#### **CONCLUSION**

This project allowed me to flex some of my JavaScript and Angular.js skills while allowing me to learn and implement several new Angular modules such as *UI Bootstrap* and *ngCookies*. Using Firebase alongside *AngularFire* was a fitting solution to allow three-way data binding between the HTML, JavaScript, and Firebase database.

##### **NEXT STEPS**

In the future, it would be nice to implement a scrolling feature that allows a user to scroll through the messages independently of the room selection on the left. There will almost always be more messages than rooms so it would be nice to not have to scroll all the way up to access the room selection. Additionally, if the application and user base were to grow, it would become increasingly important to establish logic that ensures only the most recent messages get loaded from the database upon selecting a room. This would decrease the application load time and help increase the scalability of the app.

If this application were to be used consistently by live users, there would need to be some additional logic that allows users to edit their user information such as username, email, password, etc., as well as allow them to recover their forgotten password, etc.

#### View the Project:

**<a href="https://blocchat.netlify.com/" target="_blank">Bloc Chat</a>**

##### GitHub Repo
<a href="https://github.com/dmhuebner/bloc-chat" target="_blank">bloc-chat repo</a>
