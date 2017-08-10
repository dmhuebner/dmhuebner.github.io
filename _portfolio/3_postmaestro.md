---
layout: post
title: Post Maestro
feature-img: "img/work_assets/post_maestro/post_maestro_header8.png"
thumbnail-path: "img/work_assets/post_maestro/post_maestro_thumbnail.png"
short-description: Post Maestro - Post, share, comment, vote!


---
**<a href="https://postmaestro.herokuapp.com/" target="_blank" style="font-size: 2rem;">Post Maestro</a>**

#### **SUMMARY**

Post Maestro is a Reddit-like application designed to let users share and explore posts and links from across the internet. Users can comment on public posts, use **Markdown** to style their own posts and up-vote or down-vote any posts they come across. Post Maestro was built with *Ruby on Rails*.

{:.center}
![]({{ site.baseurl }}/img/work_assets/post_maestro/post_maestro_thumbnail.png)

#### **TECHNOLOGIES USED**

Ruby, Ruby on Rails, HTML5, CSS3, JavaScript, Git

#### **EXPLANATION**

The goal of this project was to build an application modeled after <a href="http://reddit.com" target="_blank">Reddit</a> to practice building CRUD applications with *Ruby on Rails*. It was created according to user stories provided in the <a href="http://bloc.io" target="_blank">Bloc</a> *Full Stack Developer* curriculum.

Post Maestro features custom user authentication and authorization using the *bcrypt* gem and uses Rails' ActiveRecord::Enum class for different user types (admin, moderator, standard, etc.) Guest users can read through posts in public topics and view user comments. Users can create a free account to create their own posts, comment on other users' posts and up or down vote posts they find interesting.

Post Maestro has a simple, modern, mobile responsive design optimized for users on any size devise.

#### **PAGES**

##### **Sign Up View:**

Users can either sign up to create a new free account to start posting and exploring Post Maestro or sign in with their existing account.

{:.center}
![]({{ site.baseurl }}/img/work_assets/post_maestro/post_maestro_signup.png)

##### **Sign In View:**

{:.center}
![]({{ site.baseurl }}/img/work_assets/post_maestro/post_maestro_signin.png)

Once a user is logged in they will be directed to the Topics index view where they can choose a topic, they can logout by clicking the "Logout" button in the top right. Logging out destroys the user session.

##### **Topics index:**


{:.center}
![]({{ site.baseurl }}/img/work_assets/post_maestro/post_maestro_topics.png)

Once a user chooses a topic, they can read, comment, and mark posts as 'favorite' as well as make posts of their own.

##### **ActionMailer - Favorite posts email notifications:**

Once a user *favorites* a post, an ActionMailer is used to send them email notifications when other users comment on it.

##### **Mobile Responsive Design:**

Post Maestro was created with a mobile-first, responsive design using *Bootstrap*.

{:.center}
![]({{ site.baseurl }}/img/work_assets/post_maestro/post_maestro_mobile_view.png)

<!-- #### **SOLUTION** -->

#### **CONCLUSION**

This project allowed me to demonstrate foundation programming and web development skills using Ruby on Rails and RESTful MVC architecture.

##### **NEXT STEPS**

#### View the Project:

**<a href="https://postmaestro.herokuapp.com/" target="_blank">Post Maestro</a>**

##### GitHub Repo
<a href="https://github.com/dmhuebner/post-maestro" target="_blank">Post Maestro repo</a>
