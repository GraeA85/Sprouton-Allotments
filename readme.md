# Sprouton Allotments

Sprouton Allotments are a community run allotment site for veteran and beginner allotmenteers to create, grow and showcase their garden and allotment sites. The website is targeted at existing Sprouton Allotment owners to keep up to date with allotment developments, as well as budding gardeners hoping to get their hands dirty and jump into an allotment of their own. The website is designed to inform people about the allotment site, what can be done with an allotment and place themselves on a waiting list for an allotment in the future. 

# User Experience Design

## User stories

### First Time Visitor Goals

 - As a First Time user, I want to easily understand the main purpose of the site and learn more about the allotment site.
- As a First Time user, I want to be able to navigate throughout the site pages to find relevant content.
- As a First Time user, I want to view the website and content clearly on the device I am currently using and switch between devices and have the webpage be responsive.
- As a First Time user, I want to find out about the allotment site, how to get an allotment and some beginner tips.

### Returning Visitor Goals

- As a Returning user, I want to apply for an allotment, if I haven't already.
- As a Returning user, I want to contact the allotment owners to ask any questions I might have
- As a returning user, I want to get a list of the equipment that I need and see what is avaiable to buy in the allotment shop.

### Frequent Visitor Goals

- As a Frequent user, I want to check to see if there are any upcoming changes to the allotment site.
- As a Frequent user, I want to check what stock the allotment shop has or contact the allotment shop for them to order an item in for me.
- As a Frequent user, I want to view the image gallery to see if my allotment is being showcased.

## Structure

## Features 

- __Navigation Bar__

  - The navigation bar is present across all three pages of the Sprouton Allotment website. It is fully responsive and includes links to the home page, image gallery and the allotment application page. The navigation bar is in a fixed position therefore always visible to the user when scrolling the page. This is effective UX design, preventing the user to have to scroll back to the top of the page manually, or rely on auto-scoll buttons placed on the website. The navigation bar shrinks to a "hamburger" icon and presents the links in a drop-down menu when the website is viewed on smaller screens such as a mobile phone or smaller tablet.
  THe background image of the navigation bar is responsive and changes to a different image on smaller screens - this is for aesthetic reasons only. I have applied a filter to the background image which allows for the links to easily stand out against the background.

  | As a first time user its important that I can navigate through the entire website easily - If I somehow get lost then I should be able to return to the homepage. I should be able to get to each page of the website from my current page.


- __The Home page__

  - The Home page is broken up into sections. The first section is "Our Allotment Story" giving the user some background and current information regarding the allotment site. It also includes an embedded google map to show the location of the Allotment Site. I have used font awesome icons relevant to each section (the story book icon to represent the background story of the allotment site).
  The second section introduces the website visitor to the allotment committee - briefly explaining their role, names and contact information. I have included a photograph to allow existing site owners to recognise the committee members whenever they meet in person. This also gives new visitors to the site a prosepective of the owners and the mutual ideals of the allotment site. 
  Each section is succinct as to give the user enough information without information overload.
  The third section of the website is about the allotment site itself. Giving the website user information on the number of allotments available, the sizes available and other important details about the site. This is accompanied by an image of the allotment site layout which gives new users their bearings and existing owners a handy map. 
  The fourth section gives the user information on the benefits of owning an allotment. I have included a video produced by the National Allotment Society, showcasing the benefits. This is included as to persuade new users to sign up for an allotment and remind existing owners about the numerous benefits of allotment ownership.
  
  - The next section is split into three parts - a getting started equipment guide, a growing guide and a stock list of the on-site allotment shop. I have presented the equipment list and allotment shop as modals that open upon clicking the button. The growing guide links to an external pdf provided by a well-established gardening company with permission to use. The modals have a close button to easily get back to the website behind and they can also be clicked away from if the user is on a desktop website. The headers of the modals are always visible to allow the user to quickly exit, rather than having to scroll back up the page.

  The Home page is fully responsive.


- __Image Gallery__

  - The image gallery page includes photographs of the allotment site, produce grown on the allotment and other relevant photos designed to visually explain the allotment site and encourage people to join the waiting list. 
  - The image are presented in a visually appealing grid box which is fully responsive. 
   

- __Waiting list application  page__

  - This page of the site allows the site visitor to apply to join the waiting list for Sprouton allotments. It includes a relevant image (soil in a heart shape being held) with a form to gather the prospective owners information. The form is fully responsive. For design purposes, the image disappears on smaller screens so the form is the main focus for the user. The form makes use of the "required" attribute to ensure all required information is inputted by the user. Once complete the user can click the submit button which will take the user to a "thank you" page. The thank you page is included to provide feedback to the user that their request has been acknowledged. The thank you page opens in a new browser tab to prevent the user losing their place on the main website - it also includes links to return to the homepage or further information on contacting the allotment site owners.
  
- __Website Footer__

 - The footer present on each page of the website includes links to Sprouton Allotments social media pages. Each link will open in a new tab to allow the user to easily switch between the two and not lose their original position on the Sprouton Allotments website.
 - The links are facebook, instagram, twiiter and YouTube.

 __Wireframes__

Using Balsamiq I created a wireframe for the website for both a desktop browser and mobile phone browser.

- Mobile device wireframe (LINK TO BE ADDED)
- Desktop browser wireframe (LINK TO BE ADDED)

## Technologies
***
## Technologies

* HTML
	* This project uses HTML as the main language used to complete the structure of the Website. The Gitpod template used was created by Code Institute
* CSS
	* This project uses custom written CSS to style the Website.
* [Bootstrap](https://getbootstrap.com/)
	* The layout of the website was created from a Bootstrap template. The CDN is present in the head of the HTML code and the Javascript script required is present at the end of the HTML code.
	* 
* [Font Awesome](https://fontawesome.com/)
	* Font awesome icons are present throughout the website - the Navbar Brand (site logo) is prefixed with a font awesome icon. Each section of the homepage uses a font awesome icon relevant to each piece of content. The icons for the bottom section of the home page each use a font awesome icon. The footer present on each page also uses font awesome icons for each of the social media links. 
* [Google Fonts](https://fonts.google.com/)
	* Google fonts are used thourhgout the webpage and are linked to in the page head. The fonts used are  *Lobster* and *IBM Plex Sans.* 
* [GitHub](https://github.com/)
	* GitHub is the hosting site used to store the source code for the Website and [Git Pages](https://pages.github.com/) is used for the deployment of the live site.
* [Gitpod](https://git-scm.com/)
	* Git is used to create and edit all code used to build the website and store assets. It also functions as version control software to commit and push code to the GitHub repository where the source code is stored.
* [TinyJPG](https://tinyjpg.com/)
	* TinyJPG is used to reduce the file sizes of images before being deployed to reduce storage and bandwith. Used on all images in the image gallery.
* [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
	* Google chromes built in developer tools are used to inspect page elements and help debug issues with the site layout and test different CSS styles. Allows the testing of features/code without editing of your own HTML/CSS.
* [balsamiq Wireframes](https://balsamiq.com/wireframes/)
	* This was used to create wireframes for 'The Skeleton Plane' stage of UX design.
* [MS PAINT](https://support.microsoft.com/en-us/windows/get-microsoft-paint-a6b9578c-ed1c-5b09-0699-4ed8115f9aa9)
    * Used to edit some of the images present on the website, mainly those used in the navigation bar.
* [Post CSS](https://postcss.org/)
    * I ran my code through this tool to ensure no errors were present and it was recommended to use to fix any errors with Ipad resolutions. 
* [Favicon](https://favicon.io/)
    * Favicon.io was used to make the site favicon - the font icon itself was taken from Font Awesome.
* [Techsini](http://techsini.com/multi-mockup/index.php)
    * tecnisih.com Multi Device Website Mockup Generator was used to create the Mock up image at the start of the README.
* 
***
For some/all of your features, you may choose to reference the specific project files that implement them.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- A members only area of the website - including seed-swaps, equipment-loan and allotment market information.

### Test Strategy 

#### Summary 

Testing is required on MilestoneProject-1 – Hair O’ The Dog MCC Responsive Website.

As this project is static and contains no back-end functionality, the testing performed will be on the visual effects and layout of the Website. Testing to be done on at least three web browsers and all screen sizes.

No elements should overlap another container div. All elements should remain on the screen at all sizes above 300px. All carousel items should be controllable with the mouse as well as sliding on a timer. 

All nav links should direct to the correct html pages as per their names. The Home page is the exception, this one will redirect to index.html. 

All links to external websites must open in a new browser.

Testing of form validation will also be required to ensure the correct inputs are taken and that all fields are required. 

Validation of inclusion for all features included in the Structure of the Website / Wireframes must be performed.




### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 