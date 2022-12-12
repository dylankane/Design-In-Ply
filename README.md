
# Design In Ply

Design In Ply is a website for a company based in Co. Dublin. They design and make bespoke plywood furniture
for the domestic and commercial sector. This website is to help possible customers find their business, see examples 
of their work, and get a feeling for the type of company they are.It will also allow peope to see their social media
links, where they can also see more information and examples of their work. It targets people interested in one off high quality pieces of furniture. Not meant to be a place to buy off the shelf products, but to encourage people to contact them directly to commision a piece. The Idea of the site is minimalist, and clean, giving enough information to intrigue interest.
But without too much clutter, to confuse or limit what customers think the possibilities might be. Hoping the simle design will trigger the same feelings as the clean modern design of plywood funiture.

<img src="assets/readme-images/responsive-mock-up.png" alt="Image of a responsive mock up of the site across multiple devices">

***

## Features
In this section I will outline and explain the different features of the site and its layout.



__Logo__

- The Logo, which is located on the header section of each page, is a simple one. The name of the company Design In Ply, with a nice font "Poiret One" and an underline, text decoration. It is located to the far left of the header and is placed in the same location on each page, and at all screen sizes, keeping the site easy to navigate. It only moves by a few pixels right and down as the page expands above 700px wide, to keep with the open asthetics of the overall site. The logo is a hperlink to the home/landing page, clickable from anypage. As the user hovers over the logo or clicks the underline only changes to a black colour from the dim grey, it is coloured with. This underline highlight with hover was not meant to happen when I applied the pseudo hover to the logo, but it gave it some style class that I decided not to rectify.


 __Navigation Bar__


- The navigation bar, is located to the right of the header section. Containing 4 links to 3 pages. The "Home" links to the home/landing page, the projects links to a gellery of previous projects, the "About" links to the top of an about/contact page, where there is some information about the foundation and ethos of the company, and finally the "contact" links to the lower half of the about/contact page, where there is contact info along with a contact form, and live iframe of the location on google maps. The nav bar is styled with the other font used on the site "raleway". The whole word of the link higlights in black when hovered over, and and an underline appears. The colour of the text when not hovered is also in the dim grey used widely throughout the site. like the logo the nav bar links are located in the same position on all pages and on all screen sizes with some extra spacing between them on larger screen sizes. Again keeping the site intuitive. The nav bar does come closer to the left side and slightly under the logo on very small screen sizes, But I feel not cluttering the header.


__Header__

- The header section of the site is a banner accross the top, housinng the logo and the nav bar links. It is coloured in a dusty pink/terracota colour, with a slight transparency. It is fixed to the top of the viewport window, meaning it moves down with the user as they scroll through the site. Giving the user access to the other links at any point on the page, removing the need to scroll back to the top. This is where the slight transperency comes in. It doesnt completly obstruct the view of content underneath, and stops the viewport looking too small under the banner. I felt it also helped to bring the colour down through the page, keeping the theme consistent, and meaning the rest of the page can be left white and minimalist.

<img src="assets/readme-images/header-image.png" alt="Image of site's header section">


__Hero Image__

- Below the header banner there is a main / hero image. This is a place to showcase some of companies work, and imediately give meaning to the site. It lets the user quickly see what the company does and helps to create the theme of the site, showcasing their work. The image runs across the whole width of the page and and the majority of the height of the page before scrolling.
It is resopnive and takes up similar amount of real estate across all screen sizes. The image changes between to photos for larger and smaller screens. At larger sizes it is a beautiful photo of a plywood side-board in a white room. At smaller sizes below 700px wide screens, it is a stunning photo of a plywood chair again on a white / off white background, putting the furniture pieces as the main focus of the hero image. When scrolling down the image stays in the flow of the page while the header sticks to the top floating over the image. This Image is the same across all pages bar the confirmation page, only seen after the user has completed and submitted the contact form.
Laid over the hero image is some text, placed in a grey transparent box, with white text, the same off white as the background of the main body of each page. A simple tagline for the company is written here "Bespoke Plywood Furniture, Designers & Makers"
Placed in the same area of the hero image on all pages and screen sizes. The shape of the box has large rounded corners, which features on all sloid elements throughout the site, like images and form boxes. Purpose is to immediately give context to the website and what the company do.

<img src="assets/readme-images/hero-image.png" alt="Image of site's hero image" style="max-height: 300px;">

__General Company Description__

- On the home page, directly below the hero image is the first bit of text content the user will come across. It is a brief descriptioon of thecompnay and what it does. It consits of a heading in the same font as the logo with an underline decoration, in keeping with the style theme, but picked out in a different colour with a very slight contrast to the rest of the text, in a deep earthy green. Below that is a short text paragraph in the "raleway" font and in the dim grey colour.
Both the heading and paragraph is center aligned to the middle of the page. This appears the same across all screen sizes.

- sBelow this paragraph there is 4 more sections, Two more text paragraphs with headings, and two images. Each text paragraph is associated to an image by layout Each pair is in a section controlled by flex box properties in the CSS. In the smaller mobile screen sizes the appear on top of each other. First an image then text then image and finally another text parragraph. All sitting on top of each other vertically. When viewed at larger screen sizes the images move tho opposite side of the window with the text paragraphs sitting to the other sides of each image horizontally. The images stay the same size while the paragraphs spread to take up more space but still aligned centrally in the space the take up.
This keeps the site coherent and flowing in all screen sizes. The text content in these sections are more info on the company, broken into "what we do" and "why we do it" themes.

__Footer__

- The footer section aesthtcally matches the header, it is styled with the same colours for text and background as header. Again giving a nice flow to the site, making it clear the user is at the end of the page, with that background colour only been used at the top and bottom of page, framing it. Within the footer there is basic contact info. First is an email address, which is a link to bring the user to an email editor on their browser to send an email to the address. Below this is the address of the company and below that their phone number. Then underneath that is 3 icons each one a link to the companies social maedia site, Facebook , Intagram, and Youtube. Again this is kept simple with plenty of space between content, and all the relavent info needed for the user to get in touch with the company, easy to find. Always in the same place and same layout across all pages and screen sizes. The last line on the footer is just a basic copyright statement.

<img src="assets/readme-images/footer-image.png" alt="Image of site's footer section" style="max-width: 300px;">

__Previous Projects Gallery__

- The "projects" page consists of images and brief descriptions of previous work the company have completed. The page layout matches the home page with header, footer and hero images.
The gallery is made with flex box properties, making it fully responsive to different screen sizes. Changing from one image on top of each other vertically, to two side by side all the way up to 3 in a row, horizontally on the largest screen sizes. The image description in directly under each image. All the images like everywhere else on the site are styled with rounded corners, continuing the style through out the pages 

<img src="assets/readme-images/gallery-example-image.png" alt="Image of site's gallery page" style="max-height: 300px;">


__About Section__

- The about section starts at the top of a page with a in-depth description of the companies foundation and what they do. It is styles the same as the first piece of text at the bieginning of the home page, centered and coloured withe the same colours.
This page also includes the same header and hero image as the others.
Below this paragraph, are two circular photos, the only two styled differently, but still inkeeping with the rounded off corners of all the other images. these are also the only photos not  of pieces they have completed, but images of the workshop and studio. Justifing the different styling.  


__Contact Section__

- On the about page there is the contact section. linked to by its own link in the header of each page but technically the second part of the about page, hopefully bring user to this section more frequently, than been on a seperate page.
As the main contact info is on the footer of each page anyway, this section is based around a contact form, with a name email and message input field. Form is styled in keeping with sites them, with rounded corners. The textarea message input has place holder text, outlining what to add here.
Below this is an iframe element, showing a live location of the companys studio, on Google Maps. Again styled like the other images on the website.

<img src="assets/readme-images/contact-form-image.png" alt="Image of site's contact form" style="max-height: 300px;">


__Confirmation Page__

- When the conact form from the contact section has been completed, and subitted, with the name field completed and a valid email address added the user is brought to a confirmation page. this page very brifly thanks the user for getting in touch, confirms they will get a reply shortly. again encouraging the user to visit their social media links.
This page is very simple only keeping the header and footer off the other pages, losing the hero image.
The head of this page has code which redirects the user back to the home page within 10 seconds. This is stated on the page, and prevents the user having to interact with the back button while visiting the website.

***

## Future Features

- In the future there are a few features, that this site could benefit from, to increase its scope.

- In the gallery page, it would be a nice feature to be able to interact with each photo, which would open up another gallery / slideshow with more photos of that specific project, that could manually flicked through or left on a auto slide. Not in a sepeate page but just floating over the gallery page.

- The site's hero image could possibly also benifit with this being an auto slide show of images showcasing some of their pieces with different cover text over each one stating other taglines, also allowing the user to push through each photo manually.

- If the company decided to start pre making some limited small pieces of furniture or plywood accesories, the webite could incorporate an e-commerce section.

***

## Testing

- The Website has been tested, across a number of browsers, to make sure it is responding in the same way in each.
Included was Chrome, Firefox, Internet Explorer and Safari.The site is responding well and as predicted across all.
It has also be tested and viewed at mutiple screen sizes. It was designed and built for the mobile size initially, and adjusted up to larger screen sizes. As the mobile view tends to be where most of the browsing of this sort is done today.

### Validator Testing

- The finished code has been tested with online validators also. 
The Html code of each page was passed through the W3C Html Validator, returning no errors or warnings.
The CSS code has also been passed through a W3C CSS code validator, returning no errors or warnings. 
Below are the links to the results for each test.

__Html__

https://validator.w3.org/nu/?doc=https%3A%2F%2Fdylankane.github.io%2FDesign-In-Ply%2Findex.html

https://validator.w3.org/nu/?doc=https%3A%2F%2Fdylankane.github.io%2FDesign-In-Ply%2Fgallery.html

https://validator.w3.org/nu/?doc=https%3A%2F%2Fdylankane.github.io%2FDesign-In-Ply%2Fabout.html

https://validator.w3.org/nu/?doc=https%3A%2F%2Fdylankane.github.io%2FDesign-In-Ply%2Fconfirmation.html

__CSS__

https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdylankane.github.io%2FDesign-In-Ply%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en

https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdylankane.github.io%2FDesign-In-Ply%2Fgallery.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en

https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdylankane.github.io%2FDesign-In-Ply%2Fabout.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en

https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdylankane.github.io%2FDesign-In-Ply%2Fconfirmation.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en

***

## Unfixed Bugs

- The first bug that I will flag is the hero imgage cropping a bit too much of the image as sreen sizes increase. This will require more editing of the photo and possibly more styling with media queries for different screen sizes. It does take away from the overall aesthetics of the site, in particular on large desktop screens, but I feel not affecting its purpose, or user interface.

- Another issue with the site that needs attention is the main section of the landing / home page where there is 3 small paragraphs and two images giving a gereal outline of the company. The Layout here could also be improved throughout changing screen sizes. As this was designed with the mobile device as it primary target, it works fine at smaller sizes. But as the screen gets bigger, the ratio of the text and images doesnt quite look right. I used flex box properties to control this section to give me as much responsiveness as possible, but it does need more work. Not affecting the users experience of the site or its overall style and theme. 

***

## Deployment

- The Design In Ply site has been published through Git Hub pages.
Below is the main link to the site, followed by a link to each page.

https://dylankane.github.io/Design-In-Ply/

https://dylankane.github.io/Design-In-Ply/index.html

https://dylankane.github.io/Design-In-Ply/gallery.html

https://dylankane.github.io/Design-In-Ply/about.html

https://dylankane.github.io/Design-In-Ply/about.html#contact-link


- I built this project as a repository in Github using a Gitpod workspace. I deployed it through Guthub, by accessing the github pages section of the repository(on the left hand side), where you have the option to deploy/publish it by changing the branch from "none" to "main branch" (in a drop down menu). Once saved the project is deployed within a few minutes, and issued with it own url. 

***

## Credits

Here I will list sources that I used for to build the site, broken into three catagories, code, content and images.

__Code__


- Flexbox was a display property I was unfamiliar with, at the  beginning of this project. Thanks to the sources below, I was able to implement it in this project in a few places. Primarily the gallery of images, was built with the code in the "logrocket article" stripped back a bit and adjusted to meet my needs, leaving out the hover attribute to make it more mobile friendly. The other source was a video on youtube by Web Dev Simplified, to learn the basics of flexbox. This helped me with the knowledge to use this property in other areas of the project.

https://blog.logrocket.com/responsive-image-gallery-css-flexbox/

https://www.youtube.com/watch?v=fYq5PXgSsbE&t=322s

***

- When fixing the header to the top of the viewport, I found an article helping me to position it where I wanted it. After coming across some issues this helped me correct it.

https://stackoverflow.com/questions/18747466/div-disappears-on-positioning-it-fixed



- Below is a link to a page on W3Schools with information and code I used to help style elements in the contact form. With this example of code I could adapt it to style my contact form the way I wanted. Using "box-sizing" with the input[type = ].

https://www.w3schools.com/css/css_form.asp



- While designing the site, I decided I would like the "about" and "contact" sections on the one page, but linked to, with seperate navigation links in the header. Here is a source that helped me implement that. A previously question asked in a forum "stack overflow" with help from a few members.

https://stackoverflow.com/questions/17687328/getting-a-link-to-go-to-a-specific-section-on-another-page



- 10s redirect
Tim

***

 __Content__

- There are two websites of similar companies, which gave me ispiration for the design, and helped with ideas for content, and how to structure the content.  

https://www.lozidesigns.com/

https://www.madeinply.co.uk/

***

__Media__


- Below is a list of urls where I have found all the images on this site

https://www.madeinply.co.uk/ (triple-kitchen-cabinet.webp)

https://www.pureviewcarpentry.co.uk/plywood-wardrobe-with-pegboard (bedroom-plywood-units.jpg)

https://www.grundig.com/ktchnmag/blog/how-sustainable-plywood-is-changing-the-way-we-design-kitchens/ (plywood-kitchen.jpg)

https://www.lozidesigns.com/shop/p/u-desk (bent-plywood-desk.jpg)

https://www.lozidesigns.com/shop/p/shelving-system (product-collection.jpg)

https://www.justdial.com/jdmart/Kolkata/Polo-Plywood-Office-Furniture/pid-2100110989/033PXX33-XX33-160807222303-F8X1 (office-furniture-plywood.png)

https://mapayah.com/products/seat (chair.webp)







