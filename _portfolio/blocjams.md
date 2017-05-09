---
layout: post
title: Bloc Jams
feature-img: "img/work_assets/blocJams/blocJamsFeatureImage2.png"
thumbnail-path: "img/work_assets/blocJams/blocJamsThumbnail.png"
short-description: BlocJams is a lightweight music player app


---
#### **SUMMARY**

Bloc Jams is a lightweight JavaScript music player application. It has a simple, streamlined interface that can serve as a backbone or starting point to more robust music applications.

#### **EXPLANATION**

The goal of this project was to create a lightweight music player application from start to finish according to specifications in the Bloc *Full Stack Developer* curriculum. This is a simple but effective music player application that can be expanded on and customized to create more robust music applications with more complex, custom features. This application was created to practice and demonstrate my HTML, CSS and Javascript proficiency. It features a mobile responsive design, a collection feature that would hold the user's music collection, as well as an album view that includes fully functional music player capabilities.

#### **PAGES**

##### **Landing Page:**

The landing page displays a few main features and capabilities. This page implements simple CSS3 transitions to dynamically display these main features.

{:.center}
![]({{ site.baseurl }}/img/work_assets/blocJams/blocJamsLandingPage.png)

{:.center}
![]({{ site.baseurl }}/img/work_assets/blocJams/blocJamsLanding2.png)

##### **Collection Page:**

The Collection page was designed to display a user's album collection. The Collection page code is currently written to display a specified number of a given placeholder album but can easily be altered to display a user's album collection.

{:.center}
![]({{ site.baseurl }}/img/work_assets/blocJams/blocJamsCollectionPage.png)

##### **Album Page:**

The Album page was designed to display a particular album's title, artist, record label, and song list. The page utilizs the *Buzz JavaScript HTML5 Audio Library* in conjuncton with custom JavaScript code. The song player functionality allows a user to play any of the songs from the current album as well as play/pause, play the next or previous song, toggle the current position in the song and adjust the global volume.

{:.center}
![]({{ site.baseurl }}/img/work_assets/blocJams/blocJamsAlbumView.png)

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
