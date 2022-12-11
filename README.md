
# Design In Ply

Design In Ply is a website for a company based in Co. Dublin. They design and make bespoke plywood furniture
for the domestic and commercial sector. This website is to help possible customers find their business, see examples 
of their work, and get a feeling for the type of company they are.It will also allow peope to see their social media
links, where they can also see more information and examples of their work. It targets people interested in one off high quality pieces of furniture. Not meant to be a place to buy off the shelf products, but to encourage people to contact them directly to commision a piece. The Idea of the site is minimalist, and clean, giving enough information to intrigue interest.
But without too much clutter, to confuse or limit what customers think the possibilities might be. Hoping the simle design will trigger the same feelings as the clean modern design of plywood funiture.



## Features
In this section I will outline and explain the different features of the site.
Broken into two seections "exsisting features" currently live on the site, and possible "future features" that can furthure expand and improve the scope of the site.


### Existing Features
Below is a list of the current features live on the site.


### Logo


The Logo, which is located on the header section of each page, is a simple one. The name of the company Design In Ply, with a nice font "Poiret One" and an underline, text decoration. It is located to the far left of the header and is placed in the same location on each page, and at all screen sizes, keeping the site easy to navigate. It only moves by a few pixels right and down as the page expands above 700px wide, to keep with the open asthetics of the overall site. The logo is a hperlink to the home/landing page, clickable from anypage. As the user hovers over the logo or clicks the underline only changes to a black colour from the dim grey, it is coloured with. This underline highlight with hover was not meant to happen when I applied the pseudo hover to the logo, but it gave it some style class that I decided not to rectify.


### Navigation Bar

The navigation bar, is located to the right of the header section. Containing 4 links to 3 pages. The "Home" links to the home/landing page, the projects links to a gellery of previous projects, the "About" links to the top of an about/contact page, where there is some information about the foundation and ethos of the company, and finally the "contact" links to the lower half of the about/contact page, where there is contact info along with a contact form, and live iframe of the location on google maps. The nav bar is styled with the other font used on the site "raleway". The whole word of the link higlights in black when hovered over, and and an underline appears. The colour of the text when not hovered is also in the dim grey used widely throughout the site. like the logo the nav bar links are located in the same position on all pages and on all screen sizes with some extra spacing between them on larger screen sizes. Again keeping the site intuitive. The nav bar does come closer to the left side and slightly under the logo on very small screen sizes, But I feel not cluttering the header.


### Header

The header section of the site is a banner accross the top, housinng the logo and the nav bar links. It is coloured in a dusty pink/terracota colour, with a slight transparency. It is fixed to the top of the viewport window, meaning it moves down with the user as they scroll through the site. Giving the user access to the other links at any point on the page, removing the need to scroll back to the top. This is where the slight transperency comes in. It doesnt completly obstruct the view of content underneath, and stops the viewport looking too small under the banner. I felt it also helped to bring the colour down through the page, keeping the theme consistent, and meaning the rest of the page can be left white and minimalist.


### Hero Image

Below the header banner there is a main / hero image. This is a place to showcase some of companies work, and imediately give meaning to the site. It lets the user quickly see what the company does and helps to create the theme of the site, showcasing their work. The image runs across the whole width of the page and and the majority of the height of the page before scrolling.
It is resopnive and takes up similar amount of real estate across all screen sizes. The image changes between to photos for larger and smaller screens. At larger sizes it is a beautiful photo of a plywood side-board in a white room. At smaller sizes below 700px wide screens, it is a stunning photo of a plywood chair again on a white / off white background, putting the furniture pieces as the main focus of the hero image. When scrolling down the image stays in the flow of the page while the header sticks to the top floating over the image. This Image is the same across all pages bar the confirmation page, only seen after the user has completed and submitted the contact form.
Laid over the hero image is some text, placed in a grey transparent box, with white text, the same off white as the background of the main body of each page. A simple tagline for the company is written here "Bespoke Plywood Furniture, Designers & Makers"
Placed in the same area of the hero image on all pages and screen sizes. The shape of the box has large rounded corners, which features on all sloid elements throughout the site, like images and form boxes. Purpose is to immediately give context to the website and what the company do.

### General Company Description

On the home page, directly below the hero image is the first bit of text content the user will come across. It is a brief descriptioon of thecompnay and what it does. It consits of a heading in the same font as the logo with an underline decoration, in keeping with the style theme, but picked out in a different colour with a very slight contrast to the rest of the text, in a deep earthy green. Below that is a short text paragraph in the "raleway" font and in the dim grey colour.
Both the heading and paragraph is center aligned to the middle of the page. This appears the same across all screen sizes.

Below this paragraph there is 4 more sections, Two more text paragraphs with headings, and two images. Each text paragraph is associated to an image by layout Each pair is in a section controlled by flex box properties in the CSS. In the smaller mobile screen sizes the appear on top of each other. First an image then text then image and finally another text parragraph. All sitting on top of each other vertically. When viewed at larger screen sizes the images move tho opposite side of the window with the text paragraphs sitting to the other sides of each image horizontally. The images stay the same size while the paragraphs spread to take up more space but still aligned centrally in the space the take up.
This keeps the site coherent and flowing in all screen sizes. The text content in these sections are more info on the company, broken into "what we do" and "why we do it" themes.

### Footer

The footer section aesthtcally matches the header, it is styled with the same colours for text and background as header. Again giving a nice flow to the site, making it clear the user is at the end of the page, with that background colour only been used at the top and bottom of page, framing it. Within the footer there is basic contact info. First is an email address, which is a link to bring the user to an email editor on their browser to send an email to the address. Below this is the address of the company and below that their phone number. Then underneath that is 3 icons each one a link to the companies social maedia site, Facebook , Intagram, and Youtube. Again this is kept simple with plenty of space between content, and all the relavent info needed for the user to get in touch with the company, easy to find. Always in the same place and same layout across all pages and screen sizes. The last line on the footer is just a basic copyright statement.

### Previous Projects Gallery
The "projects" page consists of images and brief descriptions of previous work the company have completed. The page layout matches the home page with header, footer and hero images.
The gallery is made with flex box properties, making it fully responsive to different screen sizes. Changing from one image on top of each other vertically, to two side by side all the way up to 3 in a row, horizontally on the largest screen sizes. The image description in directly under each image. All the images like everywhere else on the site are styled with rounded corners, continuing the style through out the pages 


### About Section

The about section starts at the top of a page with a in-depth description of the companies foundation and what they do. It is styles the same as the first piece of text at the bieginning of the home page, centered and coloured withe the same colours.
This page also includes the same header and hero image as the others.
Below this paragraph, are two circular photos, the only two styled differently, but still inkeeping with the rounded off corners of all the other images. these are also the only photos not  of pieces they have completed, but images of the workshop and studio. Justifing the different styling.  


### Contact Section

On the about page there is the contact section. linked to by its own link in the header of each page but technically the second part of the about page, hopefully bring user to this section more frequently, than been on a seperate page.
As the main contact info is on the footer of each page anyway, this section is based around a contact form, with a name email and message input field. Form is styled in keeping with sites them, with rounded corners. The textarea message input has place holder text, outlining what to add here.
Below this is an iframe element, showing a live location of the companys studio, on Google Maps. Again styled like the other images on the website.


### Confirmation Page

When the conact form from the contact section has been completed, and subitted, with the name field completed and a valid email address added the user is brought to a confirmation page. this page very brifly thanks the user for getting in touch, confirms they will get a reply shortly. again encouraging the user to visit their social media links.
This page is very simple only keeping the header and footer off the other pages, losing the hero image.
The head of this page has code which redirects the user back to the home page within 10 seconds. This is stated on the page, and prevents the user having to interact with the back button while visiting the website.


### Future Features

In the future there are a few features, that this site good benefit from.

In the gallery page, it would be a nice feature to be able to interact with each photo, which would open up another gallery / slideshow with more photos of that specific project, that could manually flicked through or left on a auto slide. Not in a sepeate page but just floating over the gallery page.

The site's hero image could possibly also benifit with this being an auto slide show of images showcasing some of their pieces with different cover text over each one stating other taglines, also allowing the user to push through each photo manually.

If the company decided to start pre making some limited small pieces of furniture or plywood accesories, the webite could incorporate an e-commerce section.

## Testing


### Validator Testing

## Unfixed Bugs
styling of homepage content
?
## Deployment

## Credits

Flex box

10s re direct

contact page / section

### Content
made in ply
lozi
### Media



