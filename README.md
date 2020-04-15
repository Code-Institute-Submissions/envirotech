# Envirotech


Envirotech is a website dedicated to providing communities around the country with up-to-date, 
easy to digest information on the environmental impacts of projects happening near them. 
As our country continues to expand and more and more infrastructure is built, 
it is our duty as citizens to educate ourselves on the impact of these developments so that we can make informed appeals if necessary.

## UX
A number of careful considerations were made when designing this site. 

### To begin, our problem was defined as follows: 
- Construction is booming and more and more infrastructure is popping up across the country. As it stands, the general public have 
the oppertunity to voice their concerns/opinions on the building of such projects  (for examlpe, a road near their house). 
Engineering firms often hold 'public consultations' at which members of the public can discuss concerns. However, most people 
are left in the dark in terms of the projected impacts the project will have on them and their environment. Their only option 
is to read long, complex environmental assessments not designed for the general public. If people had access to this information 
in a way that they understood, it would help them make much more informed decisions about what will happen in their area in terms of construction. 
This level of transparency will help people feel more comfortable about new projects.
- Engineering firms often face appeals that might have already been addressed in their assessments. Directing the public to a website like 
Envirotech will help reduce the number of these kind of appeals.  

The audience for this website: The general public (specifically those who might struggle to understand complex environmental accessments)

### User Stories 
-------------------------
I am a local farmer with a large amount of land. I have heard that a large motorway might be built near my farm. I am concerned 
about how this might impact my farm. I want to know more about this project so that I can make an informed appeal if i need to.

I can go on Envirotech, look for the project in my area, and view an easy display of information about the project and how 
it might impact me, my animals, and the people around me. I can sign up to an email list so I know when the public consultation will 
be happening. If i don't see my project there, I can submit a form and the Envirotech team can look into it for me and get the information
as soon as possible. 

-------------------------

-------------------------
I am a mother of two who runs a busy schedule. There are plans to build a new bridge on my route to dropping the kids to school. 
I am concerned about traffic disruptions in the area. 

I can go on Envirotech and under the Human health and population section, I will find information about possible traffic disruptions and
how I can plan ahead. If I have any questions, I can fill out the contact us form on the website and someone will get back to me. 

-------------------------

## Wireframes 

Some mockets were drawn up in Adobe UX.
They can be found at /mockup

/mockup/home-page.png 
/mockup/project-page.png


## Design 

The nature of the webiste heavily informed design decisions 

### Color Scheme 
This is an informative website - not designed to sell or grab attention while also not looking too plain. The color scheme was choosen 
as simple, environment related, and not to distract from the information but rather to dress it up slightly. 

### Fuctionality 
The user journey is designed to be as simple to understand as possible (given that the user could potentially be someone completely unfamiliar with technology)
Buttons are large and descriptive, the benefits and function of the website are clearly laid out on the home page. 

To catch the younger audience and potentially build awareness, social media links are included throughout the website. However, 
they are not the main focus as the anticipated audience is over 30 (home owner, community active). 


## Features
In this section, you should go over the different parts of your project, and describe each in a sentence or so.

### Existing Features
Infographic - The interactive infographic at the top of the miain page allows the users to gain a good basic understanding 
of the various stages a construction project will go through and at what point they can have their say. 

Contact us - Allows the user to fill out a form and get in touch with Envirotech 

Website explaination - The 4 sectioned 'How does Envirotech work' gives the user a breakdown of how and why the website is valuable to them

Explore project - Allows the user to access detailed information on the project (broken down into sections they can understand)

Email Alerts - 'Notify about public consultations' button allows the user to sign up for alerts relating to a particular project 

Share - Interactive share button allows the users to access the company's social media pages 


## Features Left to Implement

Form validation using Javascript

Add functionality to email signup / contact-us form 

User Signup - Allows users to sign up to the website with a username and password

Community Forum - Allow users to discuss projects and ask questions 

## Technologies Used
HTML 5 / CSS 3 

Bootstrap 
https://getbootstrap.com/
Used to create responsive containers and mobile nav bar 

FontAwesome 
https://fontawesome.com/
Used for icons 


## Testing

To begin testing, I started on the home page. All interactive elements were checked first. On Desktop, any hover effects/color changes 
were checked (social media links). On mobile, the same effects were checked when links were clicked. 

I then moved on to hard link checking. Every link on the page was checked to ensure that it directed the user to the 
correct page. Every button was clicked and checked that it directed the user to the correct page.

Any links that activated modals were checked that they functioned correctly. All modals were checked to see if the 'close' buttons 
function correctly. 

The site was then tested on multiple screen sizes and orientations (horizontal & vertical) using Chrome Developer Tools. All text was checked to make sure it was easily readible on any screen
size. Item spacing was checked to make sure there was sufficient spacing between all elements on all screen sizes.

The 'preview' list of projects that strecthes across the full screen of a desktop is not needed on smaller screens. I checked that 
items added to the 'd-none d-md.. etc' appeared and disappeared as expected. 

The text at the top of the screen was reformatted on larger screens to make it more readible and stylish. I checked that this restyling occured
when expected. 

I checked that images did ot become distorted when viewed on larger screens. 

I hovered over all interactive 'tooltips' on desktop and clicked them on mobile to check that they function as expcected.  

Form Submissions were checked for the following:
- All required feels are marked as so and must be filled in before submission is possible 
- Emails are checked using HTML5 to ensure that they include an '@' before submission 
- Drop down menus were clicked ato sure proper functioning  

### Bugs or Issues left to fix
- It was not possible to validate the html form on client side (HTML5 (without javascript)) while also displaying a success message in the form of a modal when a form is submitted (data toggle)
For now - The form model just closes upon submission


## Deployment
I used git init  to initialise a local repository 
I used git add . - to add the base directory of project code into the local git repository
I used git commit -m ".." to commit to the local repository with a message containing information on the version
I used git push to push the local repository to the remote repositiry on GitHub

I then activated the site as public on GitHub Pages

## Credits
Content
All content is original (with the help of an environmental scientist)
Media
The photos used in this site are all copyright free - taken from sites such as pixabay.com 
