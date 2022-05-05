<h1 align="center"> Milestone Project 1 - User Centric Frontend Development</h1>

<div align="center">
  <a href="../issues" target="_self"><img alt="GitHub issues" src="https://img.shields.io/github/issues/nicobrown/milestoneproject1"></a>
  <a href="../issues?q=is%3Aissue+is%3Aclosed" target="_self"><img alt="GitHub closed issues" src="https://img.shields.io/github/issues-closed-raw/nicobrown/milestoneproject1"></a>
  <a href="../commits/main" target="_self"><img alt="GitHub commits" src="https://img.shields.io/github/commit-activity/y/nicobrown/milestoneproject1"></a>
  <a href="../licence.md" target="_self"><img alt="Licence" src="https://img.shields.io/github/license/NicoBrown/MilestoneProject1"></a>
</div>
<br> 
<div align="center">
[View the live project here.](https://nicobrown.github.io/MilestoneProject1/)

<hr>
<br>  
  
![image](https://user-images.githubusercontent.com/86722075/166667697-200ee409-935c-4eac-9c13-fb0280ccbfbd.png)
</div>
<br> 

## Introduction

This is the website for a fictional gym business based in Bristol, the purpose of the webiste is to give information to members on the gym location, pricing and facilities. The site was developed using HTML and CSS and is responsive on a range of devices, making it easy to navigate for customers.

## Design

### Colours
The site colour palette was chosen to be bold with colour primarily being used for icons and highlights throughout the site.
<br>
![image](https://user-images.githubusercontent.com/86722075/166670226-3a68b168-850d-4d2c-a788-128dcf1c0b1c.png)
<br>
The colour choices can be seen here on [Coloors.](https://coolors.co/0b3954-bfd7ea-ff6663-e0ff4f-fefffe) 

### Layout
The sites layout was developed using bootstraps grid system.


## Features
### Naviagtion
The sites navigation was responsive and changed depending on the screen resolution. At larger screen sizes the navbar looked like the below:
<br>
![image](https://user-images.githubusercontent.com/86722075/166831527-c60f3b0a-a4ea-4d7d-852b-55665796f121.png)

For tablets and medium screens the navbar was simplified, and for mobile screens it was removed and a dropdown menu was added in a fixed position on screen:
<br>
![image](https://user-images.githubusercontent.com/86722075/166832149-c504253f-afff-4472-87e8-3482459f08c3.png)
 
I wanted the inital screen to have as much information as possible and act as a miniture website, an arrow button was included at the bottom of the screen to take you to the about section below the hero video.

### About section
The first section was a short explanation on the gym and the benefits of excercise
![image](https://user-images.githubusercontent.com/86722075/166832520-5bc67a8c-18c2-4661-9f97-b7ffc2c6b3bc.png)


### Pricing section
this section featured pricing cards showing the available membership options and features:
![image](https://user-images.githubusercontent.com/86722075/166832635-c0d5e12d-720d-4543-93cf-526d8875f4e4.png)


### Gallery section
The showed images of the gym equipment and helped the site visiter to understand the facilities.
![image](https://user-images.githubusercontent.com/86722075/166832760-b3ba6f4e-051a-4b36-821f-0bd9c206cb34.png)


### Contact Section
The contact section showed the contact information for the business, the location and the opening times.
![image](https://user-images.githubusercontent.com/86722075/166832897-eef42ee4-02bc-48ff-93b2-34047178cd6c.png)

### Footer Section
the footer section has links to the companies social media feeds.
![image](https://user-images.githubusercontent.com/86722075/166832995-316caeba-1210-4887-a299-d12b31d5fb9c.png)


## User Experience (UX)

-   ### User stories

    -   #### First Time Visitor Goals

        1. As a First Time Visitor, I want to easily understand the main purpose of the site.
        2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find information on the gym.
        3. As a First Time Visitor, I want to locate their social media links to see their followings on social media to determine if I am interested in joining.

    -   #### Returning Visitor Goals

        1. As a Returning Visitor, I want to find the best way to get in contact with the organisation with any questions I may have.
        3. As a Returning Visitor, I want to find community links.

    -   #### Frequent User Goals
        1. As a Frequent User, I want to check to see if there are any newly added photos or information.
        2. As a Frequent User, I want to check to see if there are any new features added.

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 5.1:](https://getbootstrap.com/docs/5.1/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the dropdown menu work.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
-   
####Lighthouse results show the site was optimised over time. the initial score was:
<br>
![image](https://user-images.githubusercontent.com/86722075/166834953-83cdfaf6-1fb7-4e9b-af2b-a3d46e8e95d2.png)
<br>
and finally after following the reccomendations in the document:
<br>
![image](https://user-images.githubusercontent.com/86722075/166906877-67a88c1f-1e02-47cc-9950-c1d92997d3b4.png)
    
The reccomendations were that the sites size be reduced, the images and video were not optimised for web. I used an online conversion process to reduce the file sizes by over 90%. I preloaded one of the images used in place of the video 


### Errors
The console was showing errors relating to a depreciated method which was noted as not being removed in the future, I used javascript to clear the console on page load.
![Screenshot 2022-05-01 132413](https://user-images.githubusercontent.com/86722075/166834845-341e4b0f-9d68-4b0b-b5bf-7a30e408c27d.jpg)

<br><br>
The local repository folders were named with capitals, when this was changed the remote repositories did not update, this caused issues with resources not being found.

### Accessibility testing
The site was run through the [webaim contract checker](https://webaim.org/resources/contrastchecker/) this resulted in three colours being flagged with not enough contrast as shown in the screenshot below. the first being shown in error, and the second two being highlight colours only used for underlines, and icons in the format shown.

![Screenshot 2022-05-03 210624](https://user-images.githubusercontent.com/86722075/166833724-9015aaa7-d4b4-4d2a-aded-ee65f6c7b26b.jpg)

### Further Testing

-   The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
-   The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
-   A large amount of manual testing was done to ensure that all pages were linking correctly.

### Known Bugs

-   The gaps between section are inconsistent

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/NicoBrown/MilestoneProject1)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/NicoBrown/MilestoneProject1)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/NicoBrown/MilestoneProject1)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

### Code

-   The full-screen hero image code came from this [StackOverflow post](https://stackoverflow.com)

-   [Bootstrap5](https://getbootstrap.com/docs/5.1/getting-started/introduction/): Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System and by using their components.

-   This ReadMe file's heading's and general layout were copied and adapted from the Code institutes [Sample Read Me](https://github.com/Code-Institute-Solutions/SampleREADME) project

- Sheilds are generated by [shields.io](https://shields.io/category/monitoring)

- Gallery - initial layout taken from [here](https://mdbootstrap.com/docs/standard/extended/gallery/)

- Google map code taken from [here](https://mdbootstrap.com/docs/b4/jquery/javascript/google-maps/) and [here](https://mdbootstrap.com/docs/b4/jquery/javascript/google-maps/)

- Background image gradient code below taken from [here](https://stackoverflow.com/a/25816846)

- Map colour filter code taken from [here]( https://www.sean-lloyd.com/post/applying-css-filters-iframe/ )

### Media

-   All Images were sourced from pixabay

### Acknowledgements

-   My Mentor for helpful feedback on the optimisation process.
