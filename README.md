# THE BEATLES - FIRST MILESTONE PROJECT (CODE INSTITUTE)

## Overview of Project
This page has been commissioned by 1960’s rock band “The Beatles”.  This interactive single scrolling web page serves is designed to<br/>
-attract new fans and engage existing fans,<br/>
-inform fans through band bios,<br/>
-showcase the bands audio-visual content/media,<br/>
-provides a plug for their social media networks,<br/>
-eliminates third party by directly advertising upcoming shows and gigs,<br/>
-and building a fan base by generating a mailing list.<br/>
This serves a central location to establish the band online presence.
 

## User experience (UX) design 
The following features are added to the website which is geared towards enhancing the users online experience through the 
bands artistic ……..  This single scrolling webpage has sections for ease of use.
Header provides a static menu that gives fans access to -<br/>
    **Home** – Serves as the initial landing page. Fans are able to access the Webpage by<br/>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.	clicking The Beatles logo direct to homepage,<br/>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.	clicking the fixed Navigation Menu to navigate through the page,<br/>
    **Fab Four** <br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Provides fans with band bios, history, facts and concert photos.<br/>
    **Audio/Video content** <br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Audio content showcases the bands music<br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Video links from their youtube channel celebrating the bands performances<br/>
    **Gigs** <br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Announce dates of upcoming shows and provides a venue to purchase the tickets directly from the site.<br/>
    **Get Updates** <br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;enables fans to sign up for the band’s latest updates.<br/>
    **Book Us**<br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Book the band for an upcoming event or party<br/>
    **Footer** provides access to <br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-The bands Social media stream<br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; -and a link to automatically take the user to the top of the webpage. <br/>
	

# User stories

 **“Rudy just heard The Beatles and wants to know about the band”**
Rudy clicks the **Fab Four** link which welcomes him to a condensed introduction. He has the option to read the extended version,
along with facts and history by clicking **Read More** link. 

**“Cathy is mesmerized with one of The Beatles song and is curious to see if they have additional music”**
Cathy clicks the **Audio/Video links** to listen and watch The Beatles music compilation.

**“Tony wants to book tickets for the upcoming The Beatles tour”**
Tony is a fan of the band and has been streaming the Audio/Visual content from the website. 
He clicks the **Gigs** link to view upcoming events and purchase tickets.
He also subscribes by clicking **Get Updates**. This provides a fan centric experience.  

**“Nick will be proposing to his fiancé and is curious to see if he can book The Beatles to make event a memorable one”**
Nick clicks the **Book Us** link and completes the questionnaire pop-up window. 
This questionnaire collects information like the event date, location and time. 
The band manager responds to Nick to confirm the event details.

**“TuPac is new to social media and is curious if The Beatles have an account”**
Tupac find the **Twitter** and **Facebook** icons listed on the bottom of the webpage. 
He is now part of the bands followers linked by social media and the websites subscription link.

#### Wireframes for Desktop and mobile version<br/>
Clicking the link below will direct you to dropbox<br/>
[Wireframes for Desktop version](https://www.dropbox.com/s/jj3v94p7aaithal/Index_Page_Wireframe.jpg?dl=0)<br/>
[Wireframes for Desktop version-About Us page](https://www.dropbox.com/s/pyuodgymoliqhtw/About_Us_Wireframe.jpg?dl=0)<br/>
[Wireframe for Mobile Version](https://www.dropbox.com/s/dqckc62uodvmusw/Mobile_Devices_Wireframe.JPG?dl=0)<br/>

#### Features
-The website is responsive and conforms to different phone and computer browsers. This has been validated on the W3C Markup Validation Service.<br/>
-The **Navigation Menu** provides a single scrollable feature with clickable link directing users to different sections.<br/>
Hovering over the links shows active status of the links. <br/>
The Navigation Menu list collapses to a burger button when viewed on smaller devices.<br/><br/>
-The **Fab Four** section displays text and photo content about the band. A **“Read More”** 
link will display a webpage with new images and more information about the band.<br/>
Only the images displayed on the Fab Four have their sources (SRC) linked to other website URL’s.<br/><br/>
-The bands audio (.wav) and all other image (.jpg) files have been downloaded to assets/audios and 
the assets/images folder respectively. The Audio controls width resizes to different devices.<br/><br/>
-**Video section** displays embedded (iframe) videos from YouTube<br/><br/>
-**Gigs section** outlines a tabular display of upcoming events and ticket status indicator. 
The display conforms to different webpage sizes. <br/><br/>
-**Get updates section** provides a fan subscription option. Java script was used to change the 
button text to Subscribed once the user mandatory fields and clicks the button to complete the process.<br/><br/>
-The **Footer** displays social media connectors as clickable icons that can be directed to the bands social networks.<br/><br/>
-Clicking the **Book Us** link in the navigation menu activates an input form on a pop up (Bootstrap modal) window.
Features include a datetime control, a drop down option for specific fields and pop-up windows confirming
the inquiry has been submitted once all the mandatory fields have been completed.<br/>

Strived to use semantic HTML5 elements to structure HTML code better.


#### Technologies used includes:
**HTML5:**  to create structure of webpage<br/>
**CSS3:**  to style webpage,Used external stylesheet,file located in assets/css/style.css <br/>
**Bootstrap v 3.3.7**- For css styling, grid, tables and responsive behavior of controls<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CDN link included from https://getbootstrap.com/docs/3.3/getting-started/<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;for controls and classes https://getbootstrap.com/docs/3.3/css/<br/>
**Javascript and JQuery:**  Used Javascript and Jquery for Changing text on button,for confirm pop up,bootstrap modal,collapse menu<br/>
**Google Fonts:**  for additional font-family options https://fonts.google.com/<br/>
**Font Awesome:** for social media icons and envelope icon  https://fontawesome.com/<br/>
**Logo font:** design https://fontmeme.com/the-beatles-font/<br/>
**Blur background images:** https://www.fotor.com/features/blur.html<br/>
**Chrome Dev tools** for inspect elements for styling purpose and media queries<br/>

#### Testing:<br/>
The single scrollable webpage is tested across the following browsers
-	Google Chrome 	(Testing successfully met requirements)
-	Firefox			(Testing successfully met requirements)
-	Internet Explorer	(Testing successfully met requirements)

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
This also included the proper email format (xxx@xx.xxx)<br/>
•	Validated the button text changed to Subscribed once the mandatory fields were updated.<br/>
[Link to Get Update Test Case](https://www.dropbox.com/s/6v9h62ztd4b22vz/TestCase%20for%20Get%20Upates%20Section.jpg?dl=0)

6) **Book us**<br/>
•	Tested the link to open up a modal.<br/>
•	Verified error message on the form when the mandatory fields were left blank. 
This also included the proper email format (xxx@xx.xxx)<br/>
•	Validated the activated button initiates a pop up acknowledgment window.<br/>
[Link to Test Case](Testing Get Updates)

7) **Footer- Social media and copyright**<br/>
•   Social media links - Clicked the social media icons i.e. Facebook, Twitter and Youtube and confirmed 
it directs you to the desired site.<br/>
•   On small devices the social media and copyright are centered on the webpage.<br/>
•   Confirmed the Back to the top link works by directing the user to the top of the webpage.<br/>

