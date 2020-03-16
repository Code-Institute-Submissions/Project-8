# User Centric Front End Development Project 
This website is designed and developed as a static portfolio website with responsive design for different media sizes.

Focus is on presenting myself to recruiters and employeers who are interested and considering to hire me as their UX/UI designer. 
# UX
Goals for myself : To present and show the skills and background I have. Ultimate goal is to get hired.

Goals for users : To browse and explore throughout the portfolio website to find out more about me and my skills. Ultimate goal is to access whether I am the suitable candidate, and hire if I am the right fit for the job.

Based on the goals identified, this website is focusing on the three strategies as below :  
* Easy to use
* Presentable
* Informative
# Features  
### Existing Features  
#### 'Home' page  
* A navbar to show the overview of the contents of the website. The navbar is fixed at the top of the website so that users can access to it at anytime while exploring.
* A short and brief self-introduction about myself on the landing page.
* Modern typographies chosen and a friendly background image used to attract users, and to make them stay to explore further about the website.
* A button placed to link directly to Resume page for those users who would like to go straight to the point.
#### 'Aabout Me' page
* Playing with words by using different colors and typographies. It enables the users to read the keywords at a glance.
* Image chosen based on which I can express and convey my message to the users.
* Shaking image effect used to give motions to the static website.
* Colorful icons added to give friendly feelings to the users.
#### 'Skills' page 
* Skill bars added to show what skills I used to create this website. Users can imply that I can perform tasks with those skills and access whether I am the suitable candidate with skills that they are looking for.
* Resume page presented directly below to the skill bars which enables the  users to further learn about my educational and career background, as well as other qualifications and features.
* A button placed for users to download a full CV with more credible infomation.
* Image, typography, icons and colors used to give colorful design effects and to give consistency in design from the previous page.
#### 'Contact' page
* A contact form placed for users to contact me or leave an inquiry directly to me in the website. Tasks can be performed simply by filling and submiting the contact form.
* Placeholders shown for the required information in the contact form.  It is to guide users when they fill the contact form and it enables easier user experiences.
* More methods of contact are available in the footer. Icons, once clicked, will redirect the users to my Github page, Linkedin, Instagram, or trigger a call to my number or to my email.
* A image, typography, icons, colors used to give friendly feelings and consistency in terms of design aspects throughout the website.
* Copytight declared in the footer.
### Features left to implement
Portfolio page will be added for continuous updates with different kind of projects which will be completed in the future.
# Technologies used
* HTML5 - used to build the structure of the website.
* CSS3 - used to give design effects and style to the website. Also, media query used for responsive design function.
* [Bootstrap 4.4](https://getbootstrap.com) - used for structure and style for the website with responsive design for different media sizes.
* [Google Fonts](https://fonts.google.com)  - used for different typographies for design effects.
* [Font Awesome](https://fontawesome.com) - used for the social media icons and an email icon used in the footer.
* [Flaticon](https://www.flaticon.com) -  used for the rest of colorful icons in the portfolio websites.
# Testing
#### Links & Buttons
The main purpose of the test on links and buttons is to ensure that there are no bronken links.
* Navbar - clicked on the navbar menus to test if the links can bring users to the clicked pages.
* Buttons - the button on the main landing page was tested if it is able to bring users to the Resume page (For other buttons, I did not assign any links)
* Icons & phone number in the footer :
   * Social Media Icons were tested whether it is correctly redirect users to the pages.
   * Email Icon was tested whether it successfully activates the default mail client on the computer for sending an email.
   * Phone number was clicked to test whether it is able to trigger a call, when the users access the website using their phones.
#### Images
The main purpose of the test on the images is to ensure that there are no broken images or images not shown.
* The background image in the main landing page was not shown when it was tested in my sister's iPhone XR. (In other family members' and friends' phone or laptio, it was nicely presented.)  
This issue is still remained unresolved :
[Error detected on iPhone XR : main background image] ()
#### Responsive Design
The main purpose of the test on the responsive disign is to ensure that the website works well and organized in different sizes of the media.
* Used 'Inspect' function from Google Chrome to test the responsive design in different sizes of the media for the below :
   * Navbar and the Skills page work well as I used Bootstrap for the structure and design.
   * However the main page was not responsive according to the different sizes. A Korean phrase which is placed on the top of the Main page was shown hidden under the navbar. Also the 'View Resume' button was out of the Main landing page. To resolve this, I tried to rebuild the main landing page with Jumbotron in Bootstrap, but it could not resolve the problem. In the end, I used media query so that they can nicely fit in responsively. 
   * Also Contact page looked not organized when it was shown on different sizes of the media. I changed the grid to 'col-sm' in Bootstrap and also align the text and Submit button to the center. After that, it looked more organized for users' view.
* All the font-size, margin, padding in CSS have been rectified to em or %, from px.
* Used media query in CSS to ensure that all are responsive in different media sizes.
* Test the website on 'Am I Responsive' (http://ami.responsivedesign.is) to virtually test before sending out the deployed URL to test on the family's and friends' laptop and phones.
* Sent the deployed URL to family members and friends to test whether the website works responsively without broken images or links in different media sizes (Test was done on laptops, Galaxy S2, iPhone XR, Oppo R11, Galaxy Tab A, and etc).
* Tested on different browsers (Google Chrome, Safari, Firefox, Internet Explorer) to ensure that the website works well :
   * Google Chrome - no issues detected as this is where I designed and developed the website
   * Safari - no issue detected
   * Firefox - no major issue detected. However the main landing page appeared nicely on the full screen only starting from 110% of view. 
   * Internet Exporer - The typography used in Korean word was not appeared as designed. I used 'Gamja Flower' font from Google Fonts for the words. However it was not shown as 'Gamja Flower' and the font size was also appeared bigger.  
This issue is still remain unresolved :
[Error detected on IE : Font used for Korean word :] ()
## Deployment
Github pages was used to host the website. Since it was deployed directly from the master branch, any chages made on the website was promptly updated accordingly.  

[My Portfolio Website](https://suchan5.github.io/Project-1/)    
[My Github Page](https://github.com/suchan5/Project-1)

#### Error faced while deploying  
All the images were not shown when I access the website using the deployed URL. I deemed it as timing issue and waited for up to few hours, but it was not working. Subsequently, I un-deployed and re-deployed. However it was still not showing the images.

It was due to the dash(/) put in front of the images. For example :
```html
<imr src="/img/bg.jpg">
```
The error was successfully resolved after removing the dash.
## Credit
#### Images
* [Unsplash](https://unsplash.com) - for main backgroundn image used in the landing page & the Lego block image used in the Resume page
* [Dribble](https://dribbble.com/shots/5025015-Lego-pop-art) - for the Lego Popart image used in the Contact page 
#### Ackowledgement
* [W3schools](https://www.w3schools.com/howto/howto_css_shake_image.asp) - for the shaking image effect used in About Me page
* [WIX](https://www.wix.com/website/templates/html/portfolio-cv) - many good examples in WIX gave me inspirations and motivation for my portfoloi website
   * [Reference 1](https://www.wix.com/website-template/view/html/1887?siteId=5d2a8f2b-b726-45f6-9db1-92596eccc9d2&metaSiteId=28a077e8-599e-452b-959b-5946202e015b&originUrl=https%3A%2F%2Fwww.wix.com%2Fwebsite%2Ftemplates%2Fhtml%2Fportfolio-cv)
   * [Reference 2](https://www.wix.com/website-template/view/html/2435?siteId=533aef86-18c8-4427-be63-ae8a2501f68a&metaSiteId=764460cd-c7fe-4f6a-a067-003262b73bd4&originUrl=https%3A%2F%2Fwww.wix.com%2Fwebsite%2Ftemplates%2Fhtml%2Fportfolio-cv)
   * [Reference 3](https://www.wix.com/website-template/view/html/2180?siteId=b7d73208-d8ee-4340-bf37-b47688493e45&metaSiteId=b4078cf5-3191-4555-99b8-4afb3f61a921&originUrl=https%3A%2F%2Fwww.wix.com%2Fwebsite%2Ftemplates%2Fhtml%2Fportfolio-cv%2F2)





