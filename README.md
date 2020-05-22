# Welcome
## Code Institute Milestone Project 1 
### Portfolio - Daiden Sacha - Full Stack Web Developer
I decided on completeing a personal portfolio relating to my desire to change my
career to Full Stack Development. It fits and I decided on this as I feel it will
be an ongoing process as my skills impove. Better to start sooner than later.

### Planning
The 5 planes of user experience was a good process in which pushed me to nut out 
various aspects of the process in a sequential order.

I identified 3 potential users of the site.
1. Recruiters looking for someone to fill positions.
2. Clients looking for freelancers to complete specified work.
3. Open source projects in need of contibutors.

From my side, I'm basically looking for oportunities to work in an environment 
that supports personal and professional development, working with the latest 
technologies. Keeping it focussed to "I need to promote the professional me".

With potential users in mind I decided that I wanted to create a 
landing page with a good first impression, simple but clear. 
Required Features.
1. One page site, not overcooked with info. 
2. Sticky navbar, there when its needed.
3. Icon links to Linkedin, Github, and Contact form.
4. Modal contact form, easy to open, doesn't navigate away from the homepage.
5. About Me, Who am I, what's my strength or skillset, and what do I do/ offer?
It should be a simple outline that someone can skim though to get a brief 
outline.
6. Resume, display and possibility to download.
7. Skills block, simple block with a simple overview of my skills, using icons
and progress bars.
8. Portfolio gallery, gallery showing examples of my work.
9. Footer with the navbar and icon links.

App of choice for creating my wireframes what Adobe XD, totally new to it, but 
quite easy to pick up and has really cool features. I went a little overboard 
with the wireframe, creating a prototype page but it was fun learning.

#### Choice: Bootstrap vs UIkit
First step, play. With an idea of what I need to create, off then to 
[Codepen](https://codepen.io/daidensacha). I wanted to get an idea of what I 
could do with Bootstrap. First a modal form, then a skills block, and a 
portfolio gallery. I realised when it came to creating the gallery that in 
Bootstrap I was limited to options I didn't like. So for comparison I started 
again creating the same prototypes with UIkit and it became my preferred option
becuase of the array of features it offered. I felt better suited my needs.

### Site Sections

#### Header Block
Full screen background image, Name, and Title with 
some icons for Adobe Design, Frontend, Backend. All structured in a kind of 
"stack".

##### Navbar
Sticky navbar, links to page sections on the left, and links with icons to 
social sites on the right. Semi-transparent, dissapears scrolling down, appears 
scrolling up.

##### About Block
With mobile first design in mind I included 2 separate images in this section, 
as the larger one by design doesn't look as nice in a mobile view, so it is 
visible on screens larger than 1200px. An alternate image is visible for smaller 
screens. 
The content is minimal, to say who I am, what my stregths are and what I do. 
Contains a button link to a modal window displaying my resume, and in that modal 
is a download button opening the pdf in a separate window to be printed or saved.

#### Skill Block
This section was much easier using Bootstrap progress bars, that said it was 
pretty easy to knock the same up using HTML and CSS, looks exactly the same. 
Also easy to adjust the percentage level in the CSS file. I would make this a 
priority to convert to SASS so it would be even easier to change the variables. 

#### Portfolio Block
Here is the primary reason I chose to go with UIkit, as it suited my need to 
display images of my previous work. The sites are on my local server, and none 
currently available on public server. I wanted to display a selection of images
just as an example. I've used an overlay that appears on hover to outline the 
skills used on the work, clicking it opens it up to full screen image with 
navigation arrows to additional images. Nice seamless background created in 
Photoshop, with UIkit drop shadow for the works.

#### Modal Contact Form
I wanted the contact to be easily opened from the home page in a modal window 
with a form, hit send and bazinga! 

#### Modal View Resume
Modal opens to show a high quality gif image of the resume, with a button to 
download the resume in a separate window to be saved or printed.






