# The Gym

The brief is to design a static website to present useful information to others using all the technology we have learnt to date on the Full Stack Developer Code Institue Course. (HTML, CSS and bootstrap)

I have decided to produce a website for a fictitious Gym. I imagine this to be a small, independant City Centre Gym.... The Gym.

The site owners aim is to attract and retain customers/users. The site users want data presented in a way that helps them to achieve their goals.

## UX

See '/assets/milestone-project-1-planning-doc.docx' for information on the UX design process and wireframes etc...

### User stories 

#### Jeff
Jeff is new to the area and looking for a local gym. He is interested in location, opening times and membership costs.  
    
- Jeff can find the address and location map easily on the 'Home' page. He can also see a larger map on the 'contact' page.
- From the 'Home' page he can get a feel for the Gym and select the 'find out more' button to link to the 'About' page where he will find all the Membership options.

#### Alice
Alice is already a member of the Gym. She wants to cancel a class she is booked on to and needs to get the phone number.

- The phone number is included in the footer of every page. It is also detailed on the 'Home' page and the 'Contact' page. It is important that this information is very easy for a User to find.

#### Fred
Fred is looking at switching Gyms as his has increased their prices. He is very keen on classes and wants to know what is available and fits in with his schedule.

- Fred can easily find class information and view and download the class timetable on the 'About' page. This can be accessed from the Nav bar or the 'find out more' button on the 'Home' page.

#### Grace
Grace has heard about the gym from a friend but wants to see more before she decides if it is for her.

- A Gallery page is included to showcase people using the gym and its equipment and enjoying the classes.
- This can be accessed from the Menu and a button below the image carosel on the 'Home' page. Hopefully these images will back up what her friend has told her and give her the confidence to give The Gym a try. 


## FEATURES

### Navbar
- Allow users to navigate to each page of the site. This is the same on each page aside from the active page setting. I utilized bootstrap navbar components and CSS to construct this. 

### Home page
- The aim is for this page to be attactive and keep the user interested. So at the top I added an image carosel, using bootstrap: https://getbootstrap.com/docs/4.3/components/carousel/ (with indicators)

- Below this I added a button link to the Gallery page - This button is not a primary focus of this page and therefore is smaller and is the same colour as the background until hovered over.  

- Next I wanted to give a snippit of information about the gym to give the user a feel for it without including too much information. Then the button below this takes the user to the 'About' page where they can find information about the membership options and classes.

- It was important for the user to find the information that they are after as quickly as possible and so I have included the location and contact information on this page also. 

### About page
- The aim of this page is to provide information regarding membership and classes. I decided to not inlude any images on this page to allow the information to be clear and simple without distractions. This is inkeeping with the desire to have a simple minimalist feel and allow the site to be easy to navigate and understand for the user whist remaining stylish.
- On this page I have made use of the bootstrap grid to allow items to be displayed nicely on differnt devices.
- I decided to add colour and invert the text to highlight each item as it is hovered on using CSS3. I believe this improves the users experience when viewing the information.
- There are 3 membership options and beneath these I have added a button that leads to the contact us page. A future enhancement would be to have the contact us form as a pop up from this button.

- Below this is the Class information. This lists the classes and information about each one.
- I have included the timetable on this page but decided that it should not display on smaller devices as the formatting was poor. Therefore there is a button that allows a PDF download on smaller devices. I have also included the option for the user to download the PDF on larger devices. 

### Gallery
- I decided to include a gallery page with all the images accross the site and some additional to motivate and encourage exisiting and new members. I have used fancybox to create this. http://fancyapps.com/fancybox/3/ 
        
- A future enhancement here could be to display these a little better and perhaps add some videos. 

### Contact
- Gym image with 'contact us' over it.
- emmbedded google map.
- contact details.
- Contact form.

### Features Left to Implement
- Add a pop out form from the 'Find out more' button on the 'Home' page.
- Improve the Timetable on the 'About'. Make more interactive. Have the class information appear when the class is hovered on on the timetable. 
- Make form function.
-Improve Gallery Page: Make images display more stylishly and add videos.

### Technologies Used

The site was developed with HTML5 and CSS3 using Microsoft Visual Studio Code.
Bootstrap4  https://getbootstrap.com/ was used to create structure, navigation, forms and buttons.
Fancybox    http://fancyapps.com/fancybox/3/  was used to display images in the Gallery page.
fontawesome https://fontawesome.com/  was used to create the social media Icons.


## TESTING

https://validator.w3.org/ was used to determine any issues in the code.
The only issues remaining in the code are with the embedded map code that was taken from 
https://www.embedgooglemap.co.uk I have left these as is as this is not my code.

Throughout the developement I was checking my code to see if it performed as I was expecting. I mostly used Google Chrome for this. I used the developer tools to check and analyse the view, functionality and user experience in different screen sizes and device simulations.

In the final stages of developement I accessed the site using IE, Firefox, Microsoft Edge and checked all the functionality.

I also checked the site on my and my partners Mobile devices. I also distributed the link to my family and close friends to assess on their devices. I got some good feedback from this and I am now confident that it has been tested on the majority of screen readers and the majority of popular devices. 

## DEPLOYMENT

For this project I have used GitHub pages to deploy the site.
when I started to create the site I created a github repository and thoughout the development I have periodically added and commited changes. 
It is a straight forward process to deploy a GitHub repository to GitHub pages.
I Logged in to the git hub website and selected the correct repository 'the-gym'. 
On the settings tab I scrolled down to the 'GitHub Pages' section. In this section I clicked on the 'source' button and selected 'master branch' as this is where the files I wanted to deploy have been commited to.

As this is a fairly small project with a limited amount of files and content I have only been using the master branch within the github repository. I understand that with more complex sites and data it may be prudent in the future to introduce different branches.
Therefore the deployed version of the site is identical to the files located within the repository.

To run locally clone repo directly by passing git clone command, onto the terminal.


## CREDITS

### Content
The text for The About Page Kettlebell section is taken from https://www.webmd.com/fitness-exercise/a-z/kettlebell-workout
- You’ll work up a sweat doing a series of fast paced cardio and strength-training moves like kettlebell swings, lunges, shoulder presses, and push-ups.

 The text for The About Page Yoga section is taken from https://www.nhs.uk/live-well/exercise/guide-to-yoga/ -->
- yoga is a safe and effective way to increase physical activity, especially strength, flexibility and balance.

The text for The About Page Pilates section is taken from: https://www.nhs.uk/live-well/exercise/guide-to-pilates/
- strengthen the body in an even way, with particular emphasis on core strength to improve general fitness and wellbeing.

###  Media

As this is not a fully functioning site I just selected images that i liked from a google image search.
For a commercial site I would find images that are free to use and reference accordingly.

The photos used in this site were obtained from ...

image1
https://www.colourbox.com/image/group-of-smiling-people-working-out-with-barbells-image-8313407

image2
https://image.freepik.com/free-photo/people-working-out-at-spinning-class_13339-2540.jpg

image3
https://o2fitnessclubs.com/wp-content/uploads/2018/10/Group-Fitness-Instructor.jpg

image4
https://cdn-images-1.medium.com/max/1200/1*XVs_x4W6U_0ze9OD3Fi6Ww.jpeg 

image5
https://s3-eu-central-1.amazonaws.com/evohp/wp-content/uploads/sites/2/2017/07/13095936/EVO_July_banner_27.jpg 

image6
https://media2.s-nbcnews.com/i/newscms/2017_36/2144546/170905-working-out-group-ac-512p_2b5db137b66bedb7f1d96c24b8ca1b8a.jpg

image7
https://leaderfitness.net/wp-content/uploads/2018/02/battle-rope.jpg

image8
https://freedesignfile.com/upload/2018/03/Young-people-working-out-in-the-gym-Stock-Photo-05.jpg

image9
https://www.fitfatherproject.com/wp-content/uploads/2017/09/storyblocks-group-of-multiracial-sports-people-working-out-with-barbells-in-the-gym_rAewgChTcb-min-2400.jpg

image10
https://images.thestar.com/content/dam/thestar/news/world/2013/01/08/7_surprising_benefits_to_working_out/gymclass.jpeg 


### Acknowledgements
I received inspiration for this project from:

https://davesgym.co.uk/ This is a gym that is local to me. As my imaginary gym 'the Gym' in my imagination is a small gym and not part of a franchise I want to look at 'competitor' sites for inspiration. I looked at this to see what sort of content there was. To be honest it feels a bit cluttered and old fashioned with dated fonts. I feel there is too much content and it isnt straightforward for the user. This helped me determine that I wanted a simple site with a nice font and limited colour pallet. 

https://the-works-gym.co.uk/ This is also an idependant gym that is local to me. 
I prefered the look of this site. It is more simplistic and attactive. However, i found some aspects of this site to be a bit 'clunky' or did not function correctly. And some of the text colours clashed and were difficult to read. 
I did like the 'contact' page and reused the text 'We are only a phone call away. We are a responsive company who like to deal with enquiries promptly' as i thought this was nice and conveyed what I wanted it to. 

I also looked at a lot of franchise gym sites to see what content was common and how it had been displayed and also what I liked and disliked as a user. I then refered to the breif and the UX UI training and stepped through the 5 planes to determine what I was going to produce. Also the meetings with my mentor helped to finalise the design. 
