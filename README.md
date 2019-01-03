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
3. Bootstrap 4 https://getbootstrap.com/ - used for responsive layout (Grid), basic styling, dropdown Navbar, image carousel, contact modal (JavaScript was required for some of these features - linked to Bootstrap 4 in <script>)
4. Google Fonts https://fonts.google.com - used for customised fonts
5. Font Awesome 5 https://fontawesome.com/ - used for links to make the site more appealing
6. Figma https://www.figma.com - used as a wireframe tool to share initial styling with client
7. Google Developer Tools, Stack-Overflow, Code-Institue Slack Community, Code-Institute module notes, Flex-box Froggy, W3C Validator, CSS Tricks - all used for reference when I encountered a bug or got stuck.
8. OnePixel.com - Stock Images and TinyPNG.com - Image Compression

Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits
Content
The text for section Y was copied from the Wikipedia article Z
Media
The photos used in this site were obtained from ...
Acknowledgements
I received inspiration for this project from X
