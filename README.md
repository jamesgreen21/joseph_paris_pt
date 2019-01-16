# Joseph Paris Personal Trainer

A comprehensive website designed to give the user a complete experience of Joe’s expertise and knowledge in personal training. The user can book consultations, select from an array of training plans and read through Joe’s latest blogs. The intention of the website is to give Joe a channel for potential clients to contact him in order to accomplish their goals, gain hints and tips, and use the site to speak with Joe and other users.

## UX
 
The site focus is on potential clients enquiring about hiring a personal trainer or looking for some advice on where to start. The website includes:
-	Detail of Joe’s background and experiences
-	Customer before/after photos and testimonials
-	Training plan options for potential clients
-	A blog section with all of Joe’s latest posts for users to gain hints and tips
-	A contact section to book consultations, training plans and review other options available

Link to wireframe document using Balsamiq: \files\ joepariswebsite.bmpr

## Features

There are currently a total of four features available on the site
 
### Existing Features

- Home Page – the ‘welcome’ page, demonstrating Joe’s abilities as a Personal Trainer, including a Bio for users to read to gain an insight into Joe’s experiences and knowledge and testimonials from clients along with their results.
- Training Plan Options – Currently gives three options for the user to select from. Each link takes the user to the ‘Contact’ page, with the intention of storing the selected option to enable a more targeted response.
- Blog – Gives access to the user to all of Joe’s latest posts, with hints and tips for free. The links to each post currently takes you to a ‘Coming Soon’ page with a link back to the Home page.
- Contact – The final completed page allows the user to input their details and submit them to allow Joe to contact them. The submission form has compulsory field settings present and upon submission, you are taken to a ‘Thanks’ page with a link back to the Home page
- Other features
- o	Link on ‘Joe Paris | Personal Trainer’ header on Navbar back to Home page.
- o	Navbar – Bootstrap nav with collapsible button on devices smaller than 992px. The navbar contains the links to the features above; Home, Training Plan Options, Blog, Contact and Login/Sign Up (currently unavailable)
- o	Promo bar that displays on the Home page (not available for mobile), with a link to the contact page. Intention for Promo code to be stored for ‘Free 30 minute consultation’
- o	Footer has another contact link button, encouraging users to share their details with the site
- o	Social medial links to Facebook, Instagram and YouTube available to the user, which open onto a separate tab 

### Features Left to Implement

- Login / Sign Up – Allow users to sign up to the website, or log in. This will be used as part of a blogging page, available for all users to edit. This will also go on to be used to prohibit users from parts of the website only available to members.

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [Bootstrap](https://stackpath.bootstrapcdn.com)
    - The project uses **Bootstrap** as part of the basic layout and structure of the website, utilising the grid system. Several components have been used from the framework, with CSS modification made to ensure a unique look and feel to the website
- [Bootstrap Font Awesome](https://fontawesome.bootstrapcheatsheets.com)
    - The **Font Awesome** add-on has been used in creating the social media icons, checklist icons and navbar icons
- [Bootstrap JS](https://stackpath.bootstrapcdn.com)
    - **Bootstrap JS** has been used in the navbar collapse functionality, to allow users on smaller devices a better UX 

## Testing

### Links

All links on the site have been tested and any unavailable currently point to a ‘coming soon’ page so as not to harm the user’s experience. 

### Nav Bar

Originally, the image heading on the Home page beneath the navbar formed part of the navbar. This was edited at a later to date to due to the fixed navbar function, which reduced the amount of screen display with the image. The navbar image was then moved into the main header of each page. This gave a mirrored looked and feel across each page, without limiting the display for the main content of each page.

### Promo Bar

The promo bar on the Home page was originally meant for all displays, however, this was changed to only larger screens as the bar became illegible on smaller devices. A ‘contact Joe’ section was instead added to the Footer of each page. This allowed users to be reminded of the feature.

### Contact Form

1. Contact form:
    1. Go to the ‘Contact’ page
    2. Try to submit the empty form and verify the Bootstrap form is working correctly to highlight in red, fields that are ‘required’
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and takes you to the Thanks page, confirming submission

### Display

The website is mobile-first responsive design, and takes on a different slightly different Home page look depending on the display size. 

For mobile devices, there is a single image with no text beneath, where larger displayers show a five image with text. This was done to make a clear definitive display between mobile and larger displays, to give an app-like feel. The five image display was considered ‘too messy’ when tested.

The other major difference is that the mobile display flows, transitioning through each section of the Home page through the use of CSS shadowing as this felt more suited when thumb scrolling down the page. Larger displays will see definitive section breaks, giving it more of a website feel.

All other pages throughout the website have been styled using a mobile-first approach, altering the amount of ‘grid’ space taken up in each element as part of the Bootstrap framework, to ensure text and images are legible.

### Bugs

The Home page did have some issues with a horizontal scrollbar displaying on different responsive displays. This was caused by a number of CSS styling that has been fixed throughout the project, namely:

1. The Home page article section – caused by the text beneath the images originally being vertical skewed, which pushed them over the body container in some displays. This feature was removed and tidied to instead have a horizontal skew, which actually works better with the site
2. The Bio section also overlapped the body container. This was caused issues with overlaying the transparent background over the image to darken the affect. Also fixed

## Deployment

I have used Cloud9 for developing the website, using the HTML and CSS dev tools on both Firefox and Google Chrome. The code has been pushed up to my GitHub site, with continuous commits throughout the project as it has progressed.

## Credits

The following links and sites have been used within the coding and development:

- https://blog.codepen.io/2016/05/13/new-instagram-logo-in-css-four-ways/
- https://www.jeremycookson.com/top-10-css-hover-effects/

### Content

- All content has been written and produced by Joe Paris

### Media

- All photos have been provided by Joe Paris

## Acknowledgments

- Thanks to Joe and his clients who provided the content and assisted with the look and feel of the site giving regular feedback