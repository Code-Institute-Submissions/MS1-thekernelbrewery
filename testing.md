# Testing

![Testing Excel File](/readme/Testing.png)

## Notes on Testing 

- The [image](/readme/Testing.png/) above is an easy to view excel document listing my own testing of each feature across a variety of resolutions and devices, further clarification on the steps taken for testing can be viewed in the [Testing each Feature](#testing-each-feature) section below.
- All browser resolutions were tested with the Vivaldi browser, and through the use of Chrome Developer Tools within Vivaldi. 
- The project has been tested on 3 physical mobile devices, listed alongside all other resolutions and browsers. 
- Individual browsers were tested only at 1920x1080, unless stated otherwise, with the addition of the browser window size reduced to make the appropriate effects take place (ie, Heroimage, Accordion, etc). 
- Safari was tested on a Macbook Pro 2015 at 2560x1600 resolution.

# Testing each Feature

- Fonts 
    - The intended fonts did not load on either Edge or Internet explorer, instead were replaced with sans-serif. 

- [Navbar](/readme/images/features/navbar.png)
    - Visible across the top of each page. 
    - Position set to fixed so that scrolling keeps the bar at the top of each page.
    - Far left features the logo of the brewery which also acts as a return to home button. 
        - At smaller resolutions, the logo is central and takes the whole width.
    - Links to other pages all pushed to right hand side. 
        - [Mobile version shows bar icon rather than full list of other pages.](/readmeimages/features/navbarmobile.png)
        - [Activating toggle icon through interaction does reveal the list.](/readme/images/features/navbarmobile2.png)
        - **Bug:** The opacity effect on the dropdown navbar menu did not occur on Internet Explorer, but did in every other testing scenario. 
    - [Change in colour to show which page is currently active.](/readme/images/features/navbaractive.png) Demonstrated on beers.html.
    
- [Footer](/readme/images/features/footers.png)
    - On the left side, an interactable link to the contact page.
    - Centre features the two societies the brewery is a member of, with external links to their respective pages. 
    - Right side includes external social media links to the breweries facebook, twitter, instagram, and untappd pages.

### *Index.html*
- [Hero Video](/readme/images/features/herovideo.png)
    - Appears at the top of the page, the very top of the video is covered by the navbar. 
    - On larger resolutions, the homepage loads with a large video playing across the page, to draw the user in and demonstrate what the website is clearly about; beer. 
    - Video should auto play and requires no interaction from the user, it plays on a continuous loop.
        - **Bug:** The Hero Video did not load at full resolution for either Edge or Internet Explorer, instead there was just white space.
- [Hero Image](/readme/images/features/heroimage.png)
    - For smaller, and mobile, resolutions, an image loads, which is taken from the inside of the brewery, and still demonstrates clearly what the website is about. 
        - **Bug:** On smaller screen sizes, from iPhone X down, the Hero Image appeared quite small on index.html. It was still there, however half the image was covered by the navbar. 
        - **Fix:** Added margin-top in style.css and media queries.
- [Latest Releases](/readme/images/features/releases.png)
    - Scroll down the page to just below the hero video or image, depending on window size.
    - Shows the 3 latest beers released by the brewery.
        - At larger window sizes, these 3 beers appear in line on the x-axis. 
        - At smaller window sizes, these 3 beers appear in line on the y-axis. 
    - Hover, or click on touch screens resolution screens, displays information about the current iteration of the beer.
        - **Bug:** The Hover Effect does work on Internet Explorer, however without a background. The white text does appear though, however this is hard to read over the image itself. 
- [Opening Hours](/readme/images/features/hours.png)
    - Scroll down below the latest releases section, and the opening hours section is clear. 
    - On the left side of the section, the title with the table below appear. 
        - At smaller window sizes, this appears centrally. 
    - On the right side of the section, an image of a dog outside the brewery is visible. 
        - At smaller window sizes, this image does not appear. 

### *Beers.html*

- Text box appears at top of the page, regardless of window size, introducing the page. 
- [Beer Cards](/readme/images/features/beers.png)
    - Beers grouped into 3 sections; Pale & Hoppy, Dark, Sour & Saison respectively. Each appears below the previous.
    - Cards used were [Bootstrap Card Components](https://getbootstrap.com/docs/4.0/components/card/)
    - Each card features an image of the appropriate beer. 
        - **Bug:** Image on each card appeared larger than necessary. 
        - **Fix:** Reduced the size of each card.
    - The descriptions explain to the user what is distinct about that style. 
        - **Bug:** Text space on each card appeared larger than necessary, with extra space only being whitespace, though only appears when using Internet Explorer. 
    - Each [button](https://getbootstrap.com/docs/4.0/components/buttons/) leads to the Brewery's already existing external shop page, allowing the user to purchase. 
    - Beers appear in line across the y-axis. 
    - In the case of the dark-section, at smaller window sizes, cards will be pushed onto separate lines, and adjusting size accordingly. 
        - **Bug:** Beers appeared all on one line and required x-axis scrolling to go across. 
        - **Fix:** Introduced the card components and introduced wrap-direction styling so that they would wrap rather than stay inline.
- [Accordion](/readme/images/features/dropdown.png)
    - At smaller resolutions, the [Bootstrap Accordion Component](https://mdbootstrap.com/docs/jquery/javascript/accordion/) organises all the cards within collapsible sections. 
    - [Toggled Accordion](/readme/images/features/mobiledropdown.png), done via clicking the title of the section, shows that as one section is active, the others minimise, to keep the users scrolling to a minimum.
    

### *Taproom.html*

- [Taplist](/readme/images/features/taplist.png) 
    - Appears on the left side of the screen at larger resolutions. 
    - At smaller/mobile resolutions, this appears centrally at the top of the page.
    - Table displaying what is currently pouring in the taproom, features all information the user should need about the offerings.
    - As window size shrinks, list shrinks accordingly, until it hits the boundary to move to the central position.
        - **Bug:** On smaller screen sizes, from iPhone X down, the taplist on taproom.html requires x-axis scrolling. 
        - **Fix:** Would be replaced by an Untappd Menu api on a full release. 
- [Map](/readme/images/features/map.png)
    - Interactable google maps api allowing the user to get directions to the brewery. Address also features.
    - Appears in the centre of the page at larger resolutions. 
    - At smaller/mobile resolutions, requires scrolling down and appears below the taplist.
    - Can be interacted with using standard google gestures, for touch screen or not. 
    - As window size shrinks, list shrinks accordingly, until it hits the boundary to move to the central position.
- [Opening Hours](/readme/images/features/taphours.png)
    - Appears on the right hand side of the screen at larger resolutions. 
    - At smaller/mobile resolutions, requires scrolling and appears below the map. 
    - As window size shrinks, list shrinks accordingly, until it hits the boundary to move to the central position.


### *Events.html*

- [Timeline](/readme/images/userstories/events.png)
    - [Bootstrap Timeline component](https://www.w3schools.com/howto/howto_css_timeline.asp) which lists for the user the events the brewery will be attending that year, with the date and address of the venue. 
    - Also features a [button](https://getbootstrap.com/docs/4.0/components/buttons/) which opens an external link to the event's ticket page. 
    - Timeline appears down the centre of the page at larger resolutions, with the boxes alternating between left and right positions. 
    - At smaller mobile resolutions, timeline moves to left side of the screen and boxes all move to centre. 
        - **Bug:** Dots appeared over the navbar when scrolling, at any resolution. 
        - **Fix:** Added z-index to the dots and made sure they were beneath the navbar. Had to add z-index to the line itself, so dots stayed on top of the line. 

### *Contact.html* 

- [Contact](/readme/images/features/contact.png)
    - In the centre of the page, large interactable form for the user to input details and message to. 
        - **Bug:** On submitting the form, lead to an error page. 
        - **Fix:** Adjusted labels to match form control.
        - **Bug:** At some resolutions, lots of white space remained beneath "Send Message" button. 
        - **Fix:** Reduced size of border around contact form to reduce white space.
    - [The Selection Menu](/readme/images/features/contactdrop.png) of the form reveals a dropdown menu to categorise themselves for the site owner. 
    - On smaller resolutions, this form remains in centre of the screen, but at the top of the page.
    - Left side of the page features the "Visit Us" box. 
    - At smaller resolutions, "Visit Us" box drops centrally to beneath the form. 
    - Right side of page features "Go Direct" box. 
        - **Bug:** As window size is reduced, second bullet point on side of "Go Direct" dropped to new line. 
        - **Fix:** Included media query to reduce text size at set breakpoints.
    - At smaller resolutions, "Go Direct" box drops centrally to beneath "Visit Us" box.
    

# Testing the User-stories

- [As a site visitor, I want to see the latest beers each time I come back to the site, so I visit more often.](/readme/images/userstories/Latestrelease.png)
    - On loading index.html, scroll down page to just below hero video/hero image. 
    - Depending on resolution, three latest beers will either appear inline across x-axis at large resolutions, or inline on y-axis at smaller resolutions.

- [As a site visitor, I want to be able to get back to the home page quickly and easily, so I don’t get lost navigating and so the site works like every other site in the world.](/readme/images/userstories/returnhome.png)
    - Regardless of page, hover over logo in either top left corner or top-centre depending on resolution. 
    - Logo opacity will fade to indicate interactibility. 
    - Click/press will then take the user to index.html

- [As a brewer, I want to be able to send a message to the brewers to suggest a collaboration.](/readme/images/userstories/brewercontact.png)
    - On contact.html, interact with large form. 
    - The "I'm a..." section features drop down selection menu. 
    - Selecting "Brewer" will inform site owner of position. 
    - "I'd like to chat about..." box can then be filled with collaboration invitation. 

- [As a distributor, I want to be able to send a message to the brewery to discuss supplying beers.](/readme/images/userstories/brewercontact.png)
    - On contact.html, interact with large form. 
    - The "I'm a..." section features drop down selection menu. 
    - Selecting "Supplier" will inform site owner of position.  
    - "I'd like to chat about..." box can then be filled with request to get distribution information. 

- [As a store owner, I want to be able to contact the brewery to have their beers direct.](/readme/images/userstories/brewercontact.png)
    - On contact.html, interact with large form. 
    - The "I'm a..." section features drop down selection menu. 
    - Selecting "Supplier" will inform site owner of position.  
    - "I'd like to chat about..." box can then be filled with request to stock beers. 

- [As a consumer, I want to be able to message the brewery if I have a problem with their beers.](/readme/images/userstories/brewercontact.png)
    - On contact.html, interact with large form. 
    - The "I'm a..." section features drop down selection menu. 
    - Selecting "Customer" will inform site owner of position.  
    - "I'd like to chat about..." box can then be filled with message informing of the issue. 

- [As a consumer, I want to be able to easily and quickly see the address, so that I can plan a visit accordingly.](/readme/images/userstories/taproom.png)
    - On contact.html, left hand box "Visit us" displays address for visiting. 
    - At smaller/mobile resolutions, this box appears below the form. 
    - On taproom.html, central map reveals address in top corner of google maps api. Also shows location on a map.
    - User can also select directions and work out how to get to the brewery easily. 
    - Map appears centrally at larger resolutions, have to scroll down to below taplist on mobile resolutions.

- [As a consumer, I want to be able to easily and quickly see the opening times, so that I can plan a visit accordingly.](/readme/images/userstories/indexhours.png) 
    - On index.html, scroll down to bottom of page. 
    - "Opening hours" box will reveal the timings for the taproom being open. 
    - On taproom.html, right hand table "Opening Hours" has all the required information. 
    - At smaller/mobile resolutions, this table appears at the bottom of the page and requires scrolling.

- [As a consumer, I want to be able to know what is available in the taproom, so that I can decide whether to plan a visit.](/readme/images/userstories/taplist.png)
    - On taproom.html, at top or centre of page depending on resolution, taplist table appears.
    - At smaller resolutions, does currently require x-axis scrolling to reveal the full table contents. 
    - Will be replaced by untappd api for full release. 

- [As a consumer, I want to be able to purchase beers directly from the brewery, for delivery to my home.](/readme/images/userstories/purchaselink.png)
    - On beers.html, scroll down to each card. 
    - Read the description to decide which style it is the user is wishing to purchase, and then click the "Purchase Here" button. 
    - The product page, from the brewery's shopify store, will open in a new tab, enabling the user to purchase the beers.

-  [As a consumer, I want to know the differences between each beer, so I know which I want to buy.](/readme/images/userstories/differentbeers.png)
    - On beers.html, scroll down to view each product card. 
    - The beers are separated into three categories; 
        - Pale & Hoppy
        - Dark
        - Sour & saison
    - The user can read the descriptions of each and understand how they each differ. 

- [As a consumer, I want to understand why some Kernel Beers share the same name and what differentiates them.](/readme/images/userstories/differentbeers.png)
    - On beers.html, scroll down to view each product card. 
    - The card describes the name and style of the beer, and describes how they can vary each time. 

- [As a site visitor, I want to be able to clearly find the social media links, so that I can view the social presence, and check beer ratings.](/readme/images/userstories/footer.png)
    - On any page, the user has to scroll down to the bottom of the page, regardless of resolution. 
    - In the footer, on the right hand side, are social media links, which will open in an external tab, for: 
        - Facebook
        - Twitter
        - Instagram
        - Untappd

- [As a consumer, I want to know which events are local to me, where I can drink the breweries beers.](/readme/images/userstories/events.png) 
    - On events.html, the user can scroll down the timeline. 
    - Each card on the timeline lists a different beer festival or event occurring throughout the year. 
    - Each card also features the address of the event so the user knows which ones are local to them. 

# Validation Testing

- HTML has been validated using [W3C HTML Validator](https://validator.w3.org/nu/) 

- CSS has been validated using [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) 

- In both instances, files were validated from local file upload. Validation through URL lead to errors and warnings in regards to bootstrap, which is of no fault regarding my code, and the reason why these errors occured is discussed on the [Bootstrap Site](https://getbootstrap.com/docs/4.5/getting-started/browsers-devices/#validators)

## Validation Testing Results 

### **Index.html**

![Index.html validation](/readme/images/validation/index.png)

### **Beers.html**

![Beers.html validation](/readme/images/validation/beers.png)

### **Taproom.html**

![Taproom.html validation](/readme/images/validation/taproom.png)

### **Events.html**

![Events.html validation](/readme/images/validation/events.png)

### **Contact.html**

![Contact.html validation](/readme/images/validation/contact.png)

### **Style.css**

![Style.css validation](/readme/images/validation/css.png)
