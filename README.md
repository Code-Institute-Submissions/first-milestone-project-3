# THE BEATLES - FIRST MILESTONE PROJECT (CODE INSTITUTE)

## Overview of Project
This page has been commissioned by the 1960’s rock band “The Beatles”.  The webpage is designed to<br/>
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-attract new and engage existing fans,<br/>
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-inform fans through band bios,<br/>
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-showcases the bands audio-visual content,<br/>
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-provides a plug for their social media networks,<br/>
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-eliminates third party resellers by directly advertising upcoming shows and gigs,<br/>
       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-and building a fan base by generating a mailing list.<br/><br/>
This serves a central location to establish the band online presence.
![IMAGE](assets/images/ScreenShot.JPG)<br/><br/>

## User experience (UX) design 
The following features are added to the website which is geared towards enhancing the users online experience while maintaining the bands artistic vision. This single scrolling webpage has sections for ease of use. The header provides a static menu that gives fans access to -<br/>
    **Home** – which serves as the initial landing page. Fans are able to access the home section by<br/>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.	clicking The Beatles logo,<br/>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.	and by clicking Home on the fixed Navigation Menu<br/>
    **Fab Four** <br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Provides fans band bios, history, facts and concert photos.<br/>
    **Audio/Video content** <br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Audio section showcases the bands audio tracks<br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- While the Video section is linked to the bands YouTube channel<br/>
    **Gigs** <br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-Announces upcoming shows and provides a venue to purchase the tickets directly from the site.<br/> 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-and provides fans a visual summary of available tickets<br/>
    **Get Updates** <br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Allows fans to sign up for the band’s latest updates.<br/>
    **Book Us**<br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Allows the fans to connect directly to the band manager for an upcoming private event or occasion<br/>
    **Footer** provides access to <br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-The bands Social media stream<br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-And a link to automatically take the user to the top of the webpage. <br/>
	

# User stories

**“Rudy just heard "The Beatles" and wants to know about the band”**<br/>
Rudy clicks the **Fab Four** link which welcomes him to a condensed introduction. He has the option to read the extended version,
along with facts and history by clicking **Read More** link. 


**“Cathy is mesmerized with one of The Beatles song and is curious to see if they have additional music”**<br/>
Cathy clicks the **Audio/Video links** to listen and watch The Beatles music compilation.


**“Tony wants to book tickets for the upcoming tour”**<br/>
Tony is a fan of the band and has been streaming the Audio/Visual content from the website. 
He clicks the **Gigs** link to view upcoming events and purchase tickets.
He also clicks **Get Updates** to join the bands subscription list . This provides a fan centric experience.  


**“Nick will be proposing to his fiancé and is curious to see if he can book The Beatles to make the event a memorable one”**<br/>
Nick clicks the **Book Us** link and completes the questionnaire pop-up window. 
This questionnaire collects information like the event date, location and time. 
The band manager responds to Nick to confirm the event details.


**“TuPac is new to social media and is curious if The Beatles have an account”**<br/>
Tupac finds the **Twitter** and **Facebook** icons listed on the bottom of the webpage. 
He is now a part of the bands followers linked via social media.

# Wireframes for Desktop and mobile version<br/>
Clicking the link below will direct you to Dropbox<br/>
[Wireframes for Desktop version](https://www.dropbox.com/s/jj3v94p7aaithal/Index_Page_Wireframe.jpg?dl=0)<br/>
[Wireframes for Desktop version-About Us page](https://www.dropbox.com/s/pyuodgymoliqhtw/About_Us_Wireframe.jpg?dl=0)<br/>
[Wireframe for Mobile Version](https://www.dropbox.com/s/dqckc62uodvmusw/Mobile_Devices_Wireframe.JPG?dl=0)<br/>

# Features
The website is responsive and conforms to different phones and browsers.<br/>
•  The **Landing Page** provides a single scrollable feature.<br/><br/>
•  The **Navigation Menu** provides an inline list of clickable links directing users to different sections on the webpage.<br/>
&nbsp;&nbsp;&nbsp;Hovering over the links shows active status of the links. <br/>
&nbsp;&nbsp;&nbsp;The Navigation Menu list collapses to a burger button when viewed on smaller devices.<br/><br/>
• The **Fab Four** section displays text and photo content about the band. <br/>&nbsp;&nbsp;&nbsp;A **“Read More”** 
is a clickable link that display a webpage with new images and more information about the band.<br/>
Only the images displayed on the Fab Four have their sources (SRC) linked to other website URL’s.<br/><br/>
• The bands audio (.wav) and all other image (.jpg) files have been downloaded to assets/audios and 
the assets/images folder respectively. The Audio controls width resizes to different devices.<br/><br/>
• **Video section** displays embedded (iframe) videos from the bands YouTube channel<br/><br/>
• **Gigs section** outlines a tabular display of upcoming events and ticket status indicator. 
The display conforms to different webpage sizes. <br/><br/>
• **Get updates section** provides a fan subscription option. Java script has been used to change the 
button text to Subscribed once the user enters all mandatory fields and clicks the button to complete the process.<br/><br/>
• The **Footer** displays social media connectors as clickable icons that can be directed to the bands social networks.<br/><br/>
• Clicking the **Book Us** link in the navigation menu activates a pop-up (Bootstrap modal) input form.
Features include a datetime control, a drop down option for specific fields and pop-up window confirming
the inquiry has been submitted once all the mandatory fields have been completed.<br/>

Strived to use semantic HTML5 elements to structure HTML code better.
Used JavaScript functions to handle events on the Subscribe button (Get Updates Section) and Book Us button(Modal Popup)


# Technologies used includes:
**HTML5:**  to create structure of webpage<br/>
**CSS3:**  to style webpage, I used external stylesheet, file located in assets/css/style.css <br/>
**Bootstrap v 3.3.7**- For css styling, I used grid, tables and responsive behavior of controls<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CDN link included from https://getbootstrap.com/docs/3.3/getting-started/<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;for controls and classes https://getbootstrap.com/docs/3.3/css/<br/>
**Javascript and JQuery:**  Used Javascript and Jquery for Changing text on button,for confirm pop up,bootstrap modal,collapse menu<br/>
**Google Fonts:**  for additional font-family options https://fonts.google.com/<br/>
**Font Awesome:** for social media icons and envelope icon  https://fontawesome.com/<br/>
**Logo font:** design https://fontmeme.com/the-beatles-font/<br/>
**Blur background images:** https://www.fotor.com/features/blur.html<br/>
**Chrome Dev tools** for inspect elements for styling purpose and media queries<br/>

# Testing:<br/>
The single scrollable webpage is tested across the following browsers
-	Google Chrome 	(Testing successfully met requirements)
-	Firefox			(Testing successfully met requirements)
-	Internet Explorer	(Testing successfully met requirements)

**Testing Tools Used**<br/>
• W3C CSS Validation Service (https://jigsaw.w3.org/css-validator/)<br/>
• W3C Markup Validation Service (https://validator.w3.org/)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Received the following 
Warning: The datetime-local input type is not supported in all browsers. Please be sure to test, and consider using a polyfill.
However the website works well on all browsers mentioned above.<br/>
• Mobile Friendly Testing Tool(https://search.google.com/test/mobile-friendly)


Testing scenarios
1)	**Landing Page(index.html) and Navigation bar:**<br>
•	The landing image fits the browser with the static Navigation menu displayed on the top. 
I used the aspect ratio method to measure the width of the image as a percentage of the overall width of the 
page.ie.(height/width)*100. The landing is responsive and conforms to the browser size. 
This was tested in Google Chrome Developer tools responsive mode on 
Galaxy S5, Pixel 2, Pixel 2XL,iPhone 5/SE, iPhone 6/7/8, iPhone Plus 6/7/8, iPhone X, iPad, iPad Pro.<br/>
•	The navigation bar collapses to a burger icon when viewed on medium and small devices. 
On hovering on each of the link the color changes to yellow this is done using pseudo-elements in CSS.<br/>
•	Tested every link on the navigation bar and verified that I was directed to the appropriate sections<br/>

2)	**Fab Four Section**<br/>
•	Clicking the “Read More” link takes me to a new webpage.<br/>
•	This responsive webpage has the same layout of header and navigation as the landing page.
The header image is made responsive on Google Chrome Developer tools in responsive mode – 
Galaxy S5, Pixel 2,Pixel 2XL,iPhone 5/SE,iPhone 6/7,8, iPhone 6/7/8 Plus, iPhone X, iPad, and iPad Pro. 
This was achieved using VH (percent of view height) units.<br/>
•	The right image is hidden when the section is resized on medium sized devices. 
This image is accessible only smaller and large devices.<br>

3)	**Audio and Video Section**<br/>
•	Tested all audio and embedded video files and they play well<br/>

4)	**Gigs Section**<br/>
•	Tested the responsive behavior of this section.<br/>
•	Since the buttons have no post method implemented, clicking the buttons has no effect<br/>

5) **Get Updates Section**<br/>
•	Verified error message on the form when the mandatory fields were left blank. 
This also included the proper email format (xxx@xx.xxx) on testing.<br/>
•	Validated the button text changed to Subscribed once the mandatory fields were updated.<br/>
[Link to Get Update Test Case](https://www.dropbox.com/s/6v9h62ztd4b22vz/TestCase%20for%20Get%20Upates%20Section.jpg?dl=0)

6) **Book us**<br/>
•	Tested the link to open up a modal.<br/>
•	Verified error message on the form when the mandatory fields were left blank. 
This also included the proper email format (xxx@xx.xxx) on testing.<br/>
•	Validated the activated button initiates a pop up acknowledgment window.<br/>
[Link to Book Us Test Case](https://www.dropbox.com/s/k6tkmkg074y0mj0/BookUs%20Test%20Case.jpg?dl=0)

7) **Footer- Social media and copyright**<br/>
•   Social media links - Clicked the social media icons i.e. Facebook, Twitter and Youtube and confirmed 
it directs you to the desired site.<br/>
•   On small devices the social media and copyright are centered on the webpage.<br/>
•   Confirmed the Back to the top link works by directing the user to the top of the webpage.<br/>

# Deployment <br/>
Project is built and developed on [Cloud9](https://ide.c9.io) workspace<br/><br/>
The files have been edited in this development instance. When ready, the changes were "deployed" to the staging instance. 
After user acceptance and testing, deploy again, this time to production.
I used git and GitHub pages for deployment <br/><br>

The following steps are followed to deploy the pages<br/>
1)	Initialised the local directory in my project as a git repository used the cloud9 terminal to perform this step<br/>
        $git init<br/>
2)	Added the files in the local repository created. And staged them for commit
        $git add .<br/>
3)	Commited the files that I have staged in the local repository.<br/>
        $git commit –m ”Initial commit”<br/>
This step is perfomed for any changes I have done to sections in webpages and stylesheets as 
well as the images and audios folder<br/>
4)	Created a new repository in Github and in the terminal, added the URL for the remote repository 
where your local repository will be pushed.<br/>
5)	On major changes I have pushed  the changes in the local repository to GitHub.
        $git push origin master<br/>
        
        
On Github <br/>
1) Click Settings of the repository hosting the project and generated the external link as below


[Link to github pages:https://github.com/nadia-solution-tracker/first-milestone-project](https://github.com/nadia-solution-tracker/first-milestone-project)<br/>
[Link to Final Deployment:https://nadia-solution-tracker.github.io/first-milestone-project/](https://nadia-solution-tracker.github.io/first-milestone-project/)<br/>

# Credits
#### Content
**FabFour Section and About us.html**- Content for this section is copied from <br/>
http://www.thebestofthebest.com.au/the-artists/the-beatles/<br/>
https://en.wikipedia.org/wiki/The_Beatles<br/>

*Media*
Image url grabbed from [Beatles-The offical website](https://www.thebeatles.com/explore?type=story_photo_album)<br/>
Video iframe have been taken from [Beatles-YOUTUBE channel](https://www.youtube.com/thebeatles)<br/>


#### Code

This project is been developed from the codes learnt throughout the course of UX design from the videos of Code Insitute.
Also referred [Bootstrap documentation](https://getbootstrap.com/docs/3.3/css/) and [W3schools](https://www.w3schools.com/)<br/>

For ReadMe file referred [README MARKUPS](https://help.github.com/articles/basic-writing-and-formatting-syntax/#styling-text)<br/>



#### Bugs and Solutions
1) The landing image and header image on the webpages would not scale responsively in the viewport,instead it would display at its true size and the user on a mobile devices
would have to scroll or swipe to see full width. I handled this issue by referring-<br/>
[Resizing-Embeds-To-Be-Responsive](https://help.issuu.com/hc/en-us/articles/115000631608-Resizing-Embeds-To-Be-Responsive).<br>
2) When the modal is opened on clicking the Book Us link it applied the model.open class to the body,however this made the body width increase
to solve this issue I copied code from-<br/>
[Body width increases when modal is opened](https://github.com/jschr/bootstrap-modal/issues/64). <br/>
3) Encountered an issue that involved scaling down a large table of content(for audios and gigs section) to fit into a mobile device view.I used the overflow-y:hidden; however the
horizontal scrollbar did not make the webpage appealing. An option used here is changing the HTML5 tables code to grid layout.This made the website more
responsive on both browser and mobile devices.<br/>
4)Also referred [Stack Overflow](https://stackoverflow.com/) occasionally.


# Acknowledgements
I would extend my sincere thanks to my mentor for giving me ideas on optimizing my webpage,However all the work was 
done by me with references made to links as mentioned in "Credits" and referring "Code Institute UX Design" videos.I also took
inspiration from the Bootstrap Project "Whiskey Drop" and "Resume Project" from Code institute as well fom [Shania Twain website]
(https://www.shaniatwain.com/now-tour-2018) and [Beatles website](https://www.thebeatles.com/).




