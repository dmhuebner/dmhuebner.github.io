---
layout: post
title: Wikiport
feature-img: "img/work_assets/wikiport/wikiport_header3.png"
thumbnail-path: "img/work_assets/wikiport/wikiport_thumbnail.png"
short-description: Wikiport - Post wikis and add collaborators!


---
**<a href="https://wikiport.herokuapp.com" target="_blank" style="font-size: 2rem;">Wikiport</a>**

#### **SUMMARY**

Wikiport is a Wikipedia-like application designed to let users post and share *Markdown* wikis. Users can sign up for a free account to post and edit *public* wikis. Users can also upgrade to a *Premium Account* which allows them to create *private* wikis and add other users as collaborators. Wikiport was built with *Ruby on Rails*.

{:.center}
![]({{ site.baseurl }}/img/work_assets/wikiport/wikiport_thumbnail.png)

#### **TECHNOLOGIES USED**

Ruby, Ruby on Rails, HTML5, CSS3, JavaScript, Git

#### **EXPLANATION**

The goal of this project was to build an application modeled after <a href="http://wikipedia.com" target="_blank">Wikipedia</a> to practice and demonstrate my proficiency building CRUD applications with *Ruby on Rails*. It was created according to user stories provided in the <a href="http://bloc.io" target="_blank">Bloc</a> *Full Stack Developer* curriculum.

Wikiport features user authentication via the robust *Devise* gem and authorization using the *Pundit* gem. Guest users can read through public wikis. Users can sign up for a free account to be able to edit and create their own public wikis. Users can upgrade to a *Premium Account* which allows them to create *private* wikis and add other users as collaborators. Wikiport integrates secure payments using the *Stripe* API.

#### **PAGES**

##### **Sign Up View:**

Users can either sign up to create a new free account to start creating and editing wikis or they can sign in with their existing account.

{:.center}
![]({{ site.baseurl }}/img/work_assets/wikiport/wikiport_signup.png)

##### **Sign In View:**

{:.center}
![]({{ site.baseurl }}/img/work_assets/wikiport/wikiport_login.png)

Once a user is logged in they will be directed to the *public wikis* index view where they can browse, edit, or create a new wiki. Users can logout by clicking the "Sign Out" button in the top right. Logging out destroys the user session.

##### **Public Wikis index:**

{:.center}
![]({{ site.baseurl }}/img/work_assets/wikiport/wikiport_public_wikis.png)

Once a user signs in they can view all of their wikis by clicking on *My Wikis*. From there, they will be able to view their public wikis, their private wikis and any private wikis for which they are a collaborator.

##### **My Wikis view:**

{:.center}
![]({{ site.baseurl }}/img/work_assets/wikiport/wikiport_my_wikis.png)

##### **Mobile Responsive Design:**

Wikiport has a simple, modern, mobile responsive design optimized for users on any size devise.

{:.center}
![]({{ site.baseurl }}/img/work_assets/wikiport/wikiport_mobile_view.png)

<!-- #### **SOLUTION** -->

#### **CONCLUSION**

This project allowed me to demonstrate foundation programming and web development skills using Ruby on Rails and RESTful MVC architecture.

##### **NEXT STEPS**

#### View the Project:

**<a href="https://wikiport.herokuapp.com" target="_blank">Wikiport</a>**

##### GitHub Repo
<a href="https://github.com/dmhuebner/wikiport" target="_blank">Wikiport repo</a>
