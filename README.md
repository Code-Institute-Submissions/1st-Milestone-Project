# 1st Milestone Project - Resume Website
## Description
---
I've wrapped up my first Project inside the Course delivered by Code Institute to become a Full Stack Web Developer. 
The scope of the Project was to develop a static website with a responsive layout using a mobile first approach.
I chose to create a Resume Site for myself as a starting point to have a more customised online presence where to showcase my future projects and work. 

The website highlights my interest in displaying information in a more diverse but also structured manner. 
Through diverse the aim was to engage the interest of visitors to scroll through all content as colorful themes, animation and effects of some elements were used throughout the website. 
In this respect I chose different background colour for each page which also matched the colour of the Navigation Bar (Sidebar) and the buttons entailed (the latter designed with nice hovering effects).

I envisioned a vertical structure sectioned in three main parts:
1) Navigation bar on the left on Tablet and Desktop view with four buttons; this moves to the top on Mobile view;
2) Image Slider in the middle, displayed only on Tablets and Desktop views and hidden on Mobile; comprises three pictures of me automatically changing in the background;
3) Content on the right, which have a constant layout of the design but presenting unique information/details: About Me, Experience and Contact (also has a Contact form on a Modal functionality from Bootstrap).


Programming languages used to put together the website are: HTML5, CSS3 and Bootstrap 4 Framework Library. 
The website although has a Contact form embbeded via a Bootstrap Modal functionality it doesn't have any back-end 
functionality. 


[My Website](https://nor8ie.github.io/1st-Milestone-Project/)


## UX
---

The website was designed to provide a quick insight into my work for existing or potential customers who would be interested in starting a work/business relationship with myself and where they could gather key details about what I do. This user category includes of course recruiters.

I went for a vertical layout to catch users' attention (as most Resume pages have a landspace layout design) and aimed to keep the this organized, each part of the page to encompass relevant information which is not very detailed and would risk to lose the interest of a reader.
The font family I chose to go with is Poppins with fallback to sans-serif, as I find it to have a modern touch with slightly rounded forms, Italic and Bold, where I used the Italic style for description and/or instruction purposes. The white color for font was used throughout the whole website for consistency and to ensure a good contrast level with the colorful backgrounds.

The specific colors the button would take when hovered over by a User are coded to reflect same coloring with the backgrounds of each page make it more intuitive for them to corelate sections with information.

I also put at the users' disposal the Image Slider showing three pictures of me as everyone is keen to put a face to the name when starting a collaboration. This was also directed to create some nice space for the browsing experience and satisfy curiosity. Initially the Slider used was a standard Carousel element from Bootstrap4 library but it gave a dull feeling not having any labels for the pictures. Thus I decided to upgrade this to the version with labels and indicators where I could insert my name and title, both with box-shadow writing paired with specific background coloring.

For a better User Experience I have animated the social media icons when hovered to create a more lively feeling of the website (suggesting interactivity) and a cool visual effect. I have also added a customised scrollbar to create a nice visual effect and emphasize this way the attention to all design details.

Lastly, to increase User Experience I changed layout for different screen sizes, of greater importance to mention the website viewed on Mobile and Tablets drops the Carousel section which is no longer displayed.
This way I would no longer have my name displayed anywhere on the website other than on Desktop view and so I created and replaced displaying "about ME" header with an animated section reading "NORBERT LANG / about myself".

Wireframes used to crop out the layout of the website (index.html page) for each screen size:

### Desktop
![](assets/wireframes-figma/desktop-view.pdf)

### Tablet
![](assets/wireframes-figma/tablet-view.pdf)

### Mobile
![](assets/wireframes-figma/mobile-view.pdf)


## Features
---
#### Current Features
As mentioned the website comprises of three individual pages with same layout, each one providing specifics as detailed below:
1. ABOUT ME - activated by pressing first button on the Navigation Bar
Section where users can see an animated line which emphasizes my age, location and my title, followed by three main columns to give them a summarized idea of what I do, how I do it and give them a few reasons why a collaboration would be of an advantage to them.
On Desktop view one section is displayed on one row, the following two side by side sharing another row, however all information gets stacked on top of each other on smaller screens.

2. EXPERIENCE - activated by pressing second button on the Navigation Bar
Section where users can find the main information about my Education and Work History. This section debutes as well as the first with an animated line to highlight at one glance a brief experience timeline (Coding/Banking) and last acquired Degree in Education.
Education and Work sections are displayed in two column side by side on Desktop view and stack on top of each when view size decreases.
These are then followed by a diagram to show my skills in different programming languages, marked up as progress circles.

3. CONTACT ME - activated by pressing third button on the Navigation Bar
Section destined to provide the manners by which users can make contact for collaboration. Alongside the main point of contacts (Address, Telephone number and Email address) the users have the option to leave a direct message via the website by filling in a Contact form which would be triggered by a button in the middle area of the page.

4. DOWNLOAD CV - activated by pressing fourth button on the Navigation Bar
I specifically thought about making the word/pdf version of the CV available to recruiters, also clients who prefer to review the information in a more conservative way.

* All three pages display a footer where social media icons (animated on hover) contain the links to my external social media profiles.


#### Future Features
* To add a Portfolio page where to include presentations and the links to other Projects as well as a gallery comprising small snapshots of these websites. 


## Technologies/Support Used
---
Below is a list of technologies I have used to build out my site.
* HTML5 - used to structure the content of my website. I tried to use semantic elements where possible to ensure the best practice.
* CSS3 - used to style the page and elements but also to achieve customized styling of default Bootstrap effects by introducing my own set of classes which then I targeted;
* [Bootstrap](https://getbootstrap.com/) - used to achieve a grid style layout for the content and to help with responsiveness of elements to tackle the mobile first approach requirements for the Project. Main areas developed using Bootstrap source were: Grid system, Navbar, Carousel, Modal Contact Form. 
* [VSCode](https://code.visualstudio.com) - This is my text editor. It has a built in terminal so I could do everything I needed to from one environment.
* [Git](https://git-scm.com) - Git was used for version control. However I managed to make it operational on my laptop only in late stages of my Project as particularly found it difficult to link to VSCode.
* [GitHub](https://github.com/) - This is where the repository is held externally. GitHub pages is used to deploy my website.
* [Javascript/JQuery](https://jquery.com/) - This was imported via the Bootstrap framework to enable me enable responsiveness of the elements, import suggested throught the material of the Course.
* [Google Fonts](https://fonts.google.com/) - used to import the font family.
* [Icon Monstr](https://iconmonstr.com/) - used this source to import all my icons used throughout the website, including social media ones (in SVG format);
* [W3Schools](https://www.w3schools.com/) - used to better understand functionality of Nav Bars, position, box-shadow properties, pseudo-elements, opacity etc.
* [YouTube](https://www.youtube.com/) - used the platform to explore recommendations for good and slick designs, ways to create animations, navigation bars, HTML and CSS tricks. Main channels used for inspiration were:
- Dev Ed (https://www.youtube.com/channel/UClb90NQQcskPUGDIXsQEz5Q);
- The Net Ninja (https://www.youtube.com/channel/UCW5YeuERMmlnqo4oq8vwUpg);
- Academind (https://www.youtube.com/channel/UCSJbGtTlrDami-tDGPUV9-w);



## Testing
---
I have intensively used the Developer Tool of my browser (Chrome) to inspect and fix the code and behaviour of elements to ensure it was inline with the concept and layout of the website.
During every stage I made sure the development was working fine across various screen sizes helping me to think of further improvements and changes to be made. 
This tool was exceptionally helpful when sorting out the behaviour of the Navigation Bar as I realized this way it was better to not display certain information or sections on smaller screens and to address in a more efficient way the breakpoints of the viewport I needed to tackle to create a smooth and easthetic transition of the content.
(for example in early stages I had addressed only 2 breakpoints 768px and 578px but later on it transpired that it was more functional to tackle 4: 992px, 769px, 578px and 575px).

To make sure the website would be responsive across different mainstream browser I've always looked up this information on the source website (www.getbootstrap.com) when I was deciding which classes and functionality to use. 
Example: initially wanted to use sticky property for the navbar to fix it to the top when website was in Mobile view but then found another solution to achieve the same result as I read sticky is not supported on multiple browsers.

For a short length of time I have linked my Project Files in the Resources tab on Developer Tool and was editing the code inside the browser to see the live output of the changes, to know these are saved in the original files and will not be lost in case the page is refreshed.
After a while though I found that resizing the windows of the browser and VSCode editor worked better in terms of faster writing the codes because of the Abbreviation Emmet code snippets made available in VSCode.

On other occasions when I was facing difficulties with my code I would check solutions on various forums such as: freecodecamp.org, stackoverflow.com or slack.com.

## Bugs
---

During the development of the Project I was not sure which grid-system (CSS or Bootstrap) to use for creating the desired layout. I have made several trials to only use CSS, as I wasn't too comfortable and clear how to use one provided by Bootstrap. Eventually I realised it would become difficult to attempt to make all the content to be responsive across devices through Media Queries.

Secondly I tried CSS-Grid system which has been nice to play around with and quite effective to achieve responsiveness but then realized I needed to use other Bootstrap elements and as advised by my mentor Reuben Ferrante it was best to use Bootstrap to create the foundation of the layout.

A serious milestone in the development of this Project I encountered with the sorting out the Navigation Bar functionality from a left hand side position in Desktop view to top horizontal on Mobile. Tried out different position properties to eventually find the "relative" value to be effective in conjunction with setting a height for the <nav ul> element and applying a formula to compute the total height of the rest of the content by substracting the height of the <nav ul> element.

I used a contact form by putting in place a Bootstrap Modal which I customized and added two "required" attributes for Email and Message fields. When typing in the email address without the "@" sign it doesn't flag up an warning message.

## Deployment
---
My website was created using VSCode text editor. 
I experienced difficulties to link GIT to VSCode locally on my machine therefore I have failed in keeping a detailed version control of my Project during development. 
Because time was of the essence and there is a limited amount of time available on Gitpod.io online code editor which is free, I kept a couple of previous versions of the index.files and style.css locally on my machine.

However when I decided the code was ready to be deployed I have copied the codes entirely on Gitpod.io editor and pushed the files up to Github from there as it didn't work to do the operation from VSCode.

* I created a new repository on Github (1st-Milestone-Project)
* In the bash terminal, entered 'git init'
* Typed in 'git add .' into the bash terminal
* Typed in 'git commit' into the bash terminal with the message initial commit
* I then followed the below steps to deploy the site to GitHub pages.

To deploy the website to GitHub pages, I followed the below steps:
* Selected the 1st-milestone-project from my GitHub dashboard.
* Selected 'Settings' from the menu bar.
* From the GitHub pages section, I chose 'master branch' from the dropdown menu.
* Once selected, the page refreshed and a link was displayed in the GitHub pages section to my wesbite.
* [Website Link](https://nor8ie.github.io/1st-Milestone-Project/)

### To run this project locally

* Follow this link to the [GitHub Repositiry](https://github.com/Nor8ie/1st-Milestone-Project)
* Click on the 'Clone or Download' button.
* Copy the URL provided.
* Open a bash terminal, move to your desired directory.
* Type 'git clone' and paste in the URL.


## Credits
---
* To my mentor, [Reuben Ferrante](https://github.com/arex18) for guiding me along the way, giving me advice and ideas on how to achieve my goals.
* [Anna Greaves](https://github.com/AJGreaves), Some of Anna's documentation that she has created herself came in very useful before and during development - I'm referring to the material on Bootstrap Grid System.
* [Figma](https://balsamiq.com/) - Used to build out wireframes for my website.
* [W3C Validator](https://validator.w3.org/#validate_by_input) - A validator used to check my HTML and CSS structure and format periodically throughout the build.
* [W3Schools](https://www.w3schools.com/) - I used this to ensure I was entering all the information required correctly in my HTML and CSS.
* [Colorlib](https://colorlib.com/) - Looked at several templates on this site to choose a vertical layout.

#### Copied Code
Code which was used in its entirety as the source code apply only in the case of Bootstrap sections such as: NavBar, Carousel, Modal.