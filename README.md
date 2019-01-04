Welcome to my First Milestone Project - The Beauty Suite
=======================================================

## Overview

I have a friend with a local business. She uses social media but was interested in raising her 'online presence', making her business appear 'professional' to customers and suppliers and providing her customers a quick and easy way to find key information on her business.

## User Experience

1. Strategy

For the client/ owner the site should...
* be professional and appealing - using colours, styles and fonts in keeping with the salon's branding
* provide information on treatments and prices
* provide information on the location and opening hours
* provide contact information
* use images specific to the salon in order to 'personalise' the website for the target audience

For the user/ customer the site should...
* be intuitive and easy to use
* provide quick access to information on the salon
* look appealing 
* connect the customer to the salon's ethos and identity
* familiarise new and potential customers with the salon

User Stories
* As a frequent customer I want to be able to check the price of a facial before my appointment
* As a new customer I want to check the location of the salon and potentially identify public transport links
* I am a customer who is planning a wedding, I'd like to be able to find out about bridal make-up at the salon and find the price of a consultation before booking an appointment
* I have seen the salon and would like to find out more about it, I'd like to look at their social media accounts and find the contact details in order to make an appointment

2. Scope

In order to create a good UX the Beauty Suite's site should...
* be developed with a mobile-first approach in order to suit the target user group
* provide links to the client's social media accounts and product sites
* provide a Google Map with a marker
* provide a contact form 
* provide a downloadable price list

Please find my initial wireframe saved in 'designprocessdocs' - this was sketched whilst in discussion with the client.
My initial mock-up on Figma is also saved there. This allowed the client to have an idea of the site theme and styling. We changed the colours slightly but still kept a neutral palette, we also intoduced a bright contrasting colour. We decided to stick with a serif font - similar to the salon's external signage.


## Features

Existing Features
1. Beauty Suite navigation bar/ dropdown menu 

I used Bootstrap 4 to create a navigation bar that would be responsive and look good on mobile. I didn't want too many choices or links in my navigation bar and I decided to keep the design neat by only linking to the pages within the site. I also ensured the navigation bar was fixed to the top of pages that scrolled to ensure the user did not have to navigate using the browser 'back' button.

2. Beauty Suite footer

I wanted a footer that allowed for quick links to the key information from the site i.e. location, price list and contact information. I used Bootstrap 4 grid to ensure it looked good in mobile and desktop formats. I also created links to the social media sites used by the client.

3. Index.html

The client and I wanted a professional and appealing landing page. I used a Bootstrap 4 carousel to slide through stock photos that outlined some of the services offered by the salon. 

4. About Us.html 

By using Bootstrap 4 I created a responsive grid layout to show images and information for the salon. The user can also find out more about the brands used by the salon - Dermalogica and Opera LED.

5. Location.html

By integrating Google Maps in an iframe, the user could see (with minimal effort) the exact location of the salon. The iframe is responsive and works equally well on mobile and desktop.

6. Treatments.html

By using display:flex I was able to ensure an easy to read treatment list which is responsive and easy to read on mobile and desktop.
I then changed this to incorporate pop-up modals - see testing section

7. Contact Us Modal

Using Bootstrap 4 I included a modal contact form, this was to enable the user to enquire for information from the salon. (As it is a front-end project it is not 'wired-up' to anything - this will be a feature to implement before the site goes live)

Features for the Future
1. The modal contact form will work - enabling the user to request information from the salon.
2. Embed social media feeds into the website in order to keep the site information and images up-to-date
3. Enable clients to book appointments through the website
4. Enable clients to purchase gift vouchers through the website

Tehnologies Used
1. HTML5 - used for creating content and basic layout and validated with W3C
2. CSS3 - used for customised styling and layout and validated with W3C
3. Bootstrap 4 https://getbootstrap.com/ - used for responsive layout (Grid), basic styling, dropdown Navbar, image carousel, contact modal (JavaScript was required for some of these features - linked to Bootstrap 4 and, through BS4, popper.js in <script>)
4. Google Fonts https://fonts.google.com - used for customised fonts
5. Font Awesome 5 https://fontawesome.com/ - used for links to make the site more appealing
6. Figma https://www.figma.com - used as a wireframe tool to share initial styling with client
7. Google Developer Tools, Stack-Overflow, Code-Institue Slack Community, Code-Institute module notes, Flex-box Froggy, W3C Validator, CSS Tricks - all used for reference when I encountered a bug or got stuck.
8. OnePixel.com - Stock Images and TinyPNG.com - Image Compression
9. Color Picker https://htmlcolorcodes.com/color-picker/ - used to find color codes and colors that complemented each other


## Testing

Throughout the process I continually tested the site, by saving my work in the IDE and running it in a browser. I used Google Developer Tools to ensure that my site was responsive and functioned in all screen sizes and that my styling was applied throughout.
I asked a selection of people to test the site, some of whom were already Beauty Suite customers, mostly these tests were completed on mobile devices...

* they liked the design and layout of the site

"It looked professional and was in keeping with the branding of the salon"

* they liked that information could be found quickly

"The map looked good, I got to it through 'Find Us' on the menu at the top, it actually worked and showed you exactly where the salon was. I then tried the map icon at the bottom and it took me to the same information, very quick."

* the client liked that customers could download the price-list

"As soon as the site opened I scrolled to the bottom and found a link to download the price-list... that was quick!"

* a tester highlighted a bug - they could not launch the modal from iphone

I changed the footer links to include the associated text, however this doesn't seem to have fixed the problem - I will continue to look into this.

* a tester found it difficult to read the treatments list, there was too much information

I remedied this by creating pop-up modals instead, ensuring that the user only saw the information they required at that point.

* testers did not enjoy makeup.html due to the images appearing very large in small screens

I fixed this by using several media queries in css to ensure that the page looked good at every breakpoint.


## Deployment

I saved my work regularly on the IDE Cloud 9. I also committed my code to GitHub at regular intervals. As someone completely new to coding and the technologies I've been using, I have found it's taken me a while to get to grips with things.
In hindsight, I do not feel that I committed my code to GitHub as much as I should have done to ensure version control or with commit messages that were specific and informing. I understand I should have made a commit after coding each new feature and will now ensure that I do this as much as possible, especially as my projects become more complex.

In order to deploy my work I opened the terminal within Cloud 9.

I initialised and set up a local git repository with the command 'git init'

I added files to my git repo with the command 'git add .'

I then commited files to the local repo with 'git commit' and wrote a message after -m, as time went on I started to be more specific with my messages as I know this would be beneficial in more complex projects or when working collaboratively.

In order to commit my code to a remote repository I had to create a new project on GitHub

I then typed into the terminal "git remote add origin" followed by "https://github.com/paperclippete/Milestone1"

I would then use "git push -u master" to push my code to my master branch as I was only using one branch

In GitHub I then published my master branch to GitHub pages, this is my deployed version. There should be no differences between the deployed version and the development version.

I am aware that I will need to continue to increase my working knowledge of git and GitHub.


## Credits

Content

All content was sourced from The Beauty Suite with the owner's permission.


Media

The photos used in this site were obtained from OnePixel.com and The Beauty Suite with the owner's permission.


Acknowledgements

I received inspiration for this project from my friend and client. I also trawled through lots of local salon websites, looking for ideas on layouts, colour schemes and fonts.

Pure Spa, based in Scotland https://www.purespauk.com/

Park West Spa, a new salon in Lanarkshire http://www.parkwestspa.co.uk/

Beauty Network, an established salon based in Lanarkshire http://www.beauty-network.co.uk/

Zeste Beauty, based in Lanarkshire https://www.zestebeautyhamilton.co.uk/

